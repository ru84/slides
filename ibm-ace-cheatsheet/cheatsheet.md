---
marp: true
paginate: true
theme: rose-pine-dawn
style: |
  code {
    font-size: 24px;
    font-family: 'PT Mono' !important;
  }
  section {
    font-size: 24px;
    font-family: 'Verdana' serif !important;
  }
---

![bg left:40% 80%](https://connect.redhat.com/s3api/prod-s3api/icon_256x256.png)

# IBM App Connect

Cheatsheet for IBM App Connect Enterprise CLI Commands

##### Slides by: [Ruchi Yadav](https://www.linkedin.com/in/dr-ruchi-yadav)

---

## Toolkit Commands

- `mqsiapplybaroverride`: Applies a BAR override.
- `mqsicreatebar`: Creates a BAR file.
- `mqsicreatemsgdefs`: Creates message definitions from a schema or data format.
- `mqsicreatemsgdefsfromwsdl`: Creates message definitions from a WSDL file.
- `mqsireadbar`: Reads a BAR file.

## Environment Setup Commands

- `mqsicreateworkdir` - Create a work directory

---

## Integration Node Commands: Part 1

- `mqsiaddbrokerinstance`: Adds a broker instance to an integration node.
- `mqsiapplybaroverride`: Applies a BAR override to a broker.
- `mqsibackupbroker`: Backs up a broker.
- `mqsicreatebroker`: Creates a broker.
- `mqsicreateexecutiongroup`: Creates an execution group.
- `mqsideletebroker`: Deletes a broker.

---

## Integration Node Commands: Part 2

- `mqsideleteexecutiongroup`: Deletes an execution group.
- `mqsimode`: Sets or displays the mode of an integration node or broker.
- `mqsireadbar`: Reads a BAR file.
- `mqsireload`: Reloads the configuration of an integration node or broker.
- `mqsiremovebrokerinstance`: Removes a broker instance from an integration node.
- `mqsirestorebroker`: Restores a broker from a backup.

---

## Database Commands

- `mqsimanagexalinks`: Manages extended authentication links.
- `mqsisetdbparms`: Sets the database parameters for an integration node.
- `mqsireportdbparms`: Retrieves the database parameters for an integration node.

---

## Security Commands: Part 1

- `mqsichangeauthmode`: Changes the authentication mode for the integration node.
- `mqsichangefileauth`: Changes the file-based authentication for the integration node.
- `mqsicredentials`: Manages user credentials for the integration node.
- `mqsireloadsecurity`: Reloads the security settings for the integration node.
- `mqsireportauthmode`: Reports the current authentication mode for the integration node.

---

## Security Commands: Part 2

- `mqsireportfileauth`: Reports the current file-based authentication settings for the integration node.
- `mqsisetdbparms`: Sets the database parameters for the integration node.
- `mqsisetsecurity`: Sets the security settings for the integration node.
- `mqsivault`: Manages security vaults for the integration node.
- `mqsiwebuseradmin`: Manages web user administration for the integration node.

---

## Start and stop commands

- `mqsistart`: Starts an integration node or broker.
- `mqsistartmsgflow`: Starts a message flow on an integration node or broker.
- `mqsistop`: Stops an integration node or broker.
- `mqsistopmsgflow`: Stops a message flow on an integration node or broker.

## List and Trace commands

- `mqsichangetrace`: Changes the trace level for an integration node.
- `mqsilist`: Lists the integration nodes, brokers, configurable services, message flows, and message sets on the local system.

---

## Migration Commands

- `mqsiextractcomponents`: Extracting an integration node configuration and resources to a work directory.

## Properties Commands

- `mqsichangeproperties`: Modifies the value of a property for an integration node resource.
- `mqsireportproperties`: Retrieves the value of a property for an integration node resource.

---

## Monitoring Commands

- `mqsichangeflowmonitoring`: Changes the monitoring properties for a flow.
- `mqsireportflowmonitoring`: Retrieves the monitoring properties for a flow.

## Statistics Commands.

- `mqsichangeflowstats`: Changes the statistics collection mode for a flow.
- `mqsichangeresourcestats`: Changes the statistics collection mode for a resource.
- `mqsireportflowstats`: Retrieves statistics for a flow.
- `mqsireportresourcestats`: Retrieves statistics for a resource.

---

## Callable Flows Commands

- `iibcreateswitchcfg`: Generates configuration files for the Switch server and connectivity agents that enable secure connectivity to the Switch server.
- `iibswitch`: Manages the Switch server, a component of IBM App Connect Enterprise that enables you to split message flow processing between different integration servers.

---

## Miscellaneous Commands: Part 1

- `ace`: Manages IBM App Connect Enterprise installations.
- `mqsibar`: Manages business process artifacts (BARs).
- `mqsiAssemblyInstall`: Installs assemblies.
- `mqsicacheadmin`: Manages IBM App Connect Enterprise cache administrators.
- `mqsichangeflowuserexits`: Changes flow user exits.
- `mqsicommandconsole`: Launches the IBM App Connect Enterprise command console.
- `mqsicreateconfigurableservice`: Creates configurable services.

---

## Miscellaneous Commands: Part 2

- `mqsicvp`: Manages configuration versions of process packages.
- `mqsideploy`: Deploys applications.
- `mqsiexplain`: Explains flow or node properties.
- `mqsipackagebar`: Packages business process artifacts (BARs).
- `mqsipushapis`: Pushes APIs to an API management server.
- `mqsireportflowuserexits`: Reports flow user exits.

---

## Read More

[Click here for Reference Documentation](https://www.ibm.com/docs/en/app-connect/11.0.0?topic=software-reference)
