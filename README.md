# Splunk ACS CLI
Admin Config Service CLI for managing splunk cloud stacks.

The Admin Config Service (ACS) provides a command line interface (CLI) that lets you perform many Splunk Cloud Platform configuration and management tasks in a self-service manner. You can use the CLI to run corresponding ACS API operations from the command line, without having to know specific API endpoint details.

### Installing

Use a prebuilt binary [from the releases page](https://github.com/splunk/acs-cli/releases) for your operating system.

On MacOS and Linux, you can install `acs` using homebrew:

```
$ brew tap splunk/tap 
$ brew install acs
```

On Windows, you can install `acs` using winget:
```
$ winget install acs-cli
```

Run 'acs version' to verify you are running the latest CLI version

Run ‘acs’ or ‘acs –help’ to get started.


### CLI configuration and workflow
ACS CLI simplifies access to multiple Splunk Cloud Platform deployments (stacks).

Here’s a sample workflow for initial CLI configuration before running CLI operations for ACS APIs.

![ACS CLI_ User Guide](https://user-images.githubusercontent.com/95648640/156843519-5825eec1-3f6c-484e-882d-f3a2b18fefd2.jpg)
Please refer to [Splunk ACS CLI docs](https://docs.splunk.com/Documentation/SplunkCloud/latest/Config/ACSCLI) for more help.
