> NOTE: This documentation is still under construction.
# The `coalesce-utils` Package
Packages contain [user-defined node types (UDNs)](https://docs.coalesce.io/docs/node-types) that can be added to your Coalesce.io Organization and then used in your [directed acyclic graph (DAG)](https://en.wikipedia.org/wiki/Directed_acyclic_graph).
The `coalesce-utils` package currently contains only the *Dynamic Table* UDN, but it will contain many more soon.
They are installed using the [`coa` CLI](https://docs.coalesce.io/docs/cli-overview) referencing the URL of the Git repository containing the package.

# Installing the `coa` CLI
Follow [these](https://docs.coalesce.io/docs/cli-setup) instructions for the installation and setup of `coa`.

# Install the `coalesce-utils` package.
> NOTE: Installing packages via the `coa` CLI is in beta and not yet available.
Request the package from Coalesce support.

Install the package using the following command:

```
coa package add https://github.com/coalesceio/coalesce-utils
```
..and the results:
```
❯ coa package add https://github.com/coalesceio/coalesce-utils
|2022-11-16T20:14:28.331Z|[CLI]|(org:cD8VVx8tnM5wf7pXvHoq; env:1; user:Pc6m1dJreHZNTj85mGxrjwVrhqp2)||info:Add package initialized. running...
|2022-11-16T20:14:28.333Z|[CLI]|(org:cD8VVx8tnM5wf7pXvHoq; env:1; user:Pc6m1dJreHZNTj85mGxrjwVrhqp2)||info:Initializing package installation...
|2022-11-16T20:14:28.334Z|[CLI]|(org:cD8VVx8tnM5wf7pXvHoq; env:1; user:Pc6m1dJreHZNTj85mGxrjwVrhqp2)||info:Cloning Coalesce package from repo URL: https://github.com/coalesceio/coalesce-utils
|2022-11-16T20:14:29.451Z|[CLI]|(org:cD8VVx8tnM5wf7pXvHoq; env:1; user:Pc6m1dJreHZNTj85mGxrjwVrhqp2)||info:Reading Coalesce package data from repo "https://github.com/coalesceio/"...
|2022-11-16T20:14:29.716Z|[CLI]|(org:cD8VVx8tnM5wf7pXvHoq; env:1; user:Pc6m1dJreHZNTj85mGxrjwVrhqp2)||info:Gathering your project workspace data for environment: 1
|2022-11-16T20:14:30.920Z|[CLI]|(org:cD8VVx8tnM5wf7pXvHoq; env:1; user:Pc6m1dJreHZNTj85mGxrjwVrhqp2)||info:Installing package using namespace "COALESCE-UTILS::"
|2022-11-16T20:14:31.139Z|[CLI]|(org:cD8VVx8tnM5wf7pXvHoq; env:1; user:Pc6m1dJreHZNTj85mGxrjwVrhqp2)||info:adding COALESCE-UTILS...building firestore updates payload...
|2022-11-16T20:14:31.140Z|[CLI]|(org:cD8VVx8tnM5wf7pXvHoq; env:1; user:Pc6m1dJreHZNTj85mGxrjwVrhqp2)||info:Cleaning up any stale package data in your project...
|2022-11-16T20:14:31.140Z|[CLI]|(org:cD8VVx8tnM5wf7pXvHoq; env:1; user:Pc6m1dJreHZNTj85mGxrjwVrhqp2)||info:Pruning workspace data: macros
|2022-11-16T20:14:31.140Z|[CLI]|(org:cD8VVx8tnM5wf7pXvHoq; env:1; user:Pc6m1dJreHZNTj85mGxrjwVrhqp2)||info:Pruning workspace data: stepTypes
|2022-11-16T20:14:31.140Z|[CLI]|(org:cD8VVx8tnM5wf7pXvHoq; env:1; user:Pc6m1dJreHZNTj85mGxrjwVrhqp2)||info:Preparing workspace data for import: macros
|2022-11-16T20:14:31.141Z|[CLI]|(org:cD8VVx8tnM5wf7pXvHoq; env:1; user:Pc6m1dJreHZNTj85mGxrjwVrhqp2)||info:Preparing workspace data for import: stepTypes
|2022-11-16T20:14:31.143Z|[CLI]|(org:cD8VVx8tnM5wf7pXvHoq; env:1; user:Pc6m1dJreHZNTj85mGxrjwVrhqp2)||info:Adding stepType: 6 as COALESCE-UTILS::6
|2022-11-16T20:14:31.143Z|[CLI]|(org:cD8VVx8tnM5wf7pXvHoq; env:1; user:Pc6m1dJreHZNTj85mGxrjwVrhqp2)||info:Applying updates to firestore...
|2022-11-16T20:14:31.503Z|[CLI]|(org:cD8VVx8tnM5wf7pXvHoq; env:1; user:Pc6m1dJreHZNTj85mGxrjwVrhqp2)||info:added COALESCE-UTILS...update successful!
|2022-11-16T20:14:31.505Z|[CLI]|(org:cD8VVx8tnM5wf7pXvHoq; env:1; user:Pc6m1dJreHZNTj85mGxrjwVrhqp2)||info:CLI Package Installation complete
```
# Contents of the `coalesce-utils` package
## Dynamic Tables
Coming Soon.