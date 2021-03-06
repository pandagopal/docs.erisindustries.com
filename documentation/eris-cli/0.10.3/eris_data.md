---

layout:     documentation
title:      "Documentation | eris:cli | eris data"

---

# eris data

Manage Data Containers for your Application.

## Synopsis

The data subcommand is used to import, and export
data into containers for use by your application.

eris data import and eris data export should be thought of from
the point of view of the container.

eris data import sends files *as is* from ~/.eris/data/NAME on
the host to ~/.eris/ inside of the data container.

eris data export performs this process in the reverse. It sucks
out whatever is in the volumes of the data container and sticks
it back into ~/.eris/data/NAME on the host.

At eris, we use this functionality to formulate little jsons
and configs on the host and then "stick them back into the
containers"


```bash
eris data
```

## Options inherited from parent commands

```
  -d, --debug[=false]: debug level output
      --machine="eris": machine name for docker-machine that is running VM
  -n, --num=1: container number
  -v, --verbose[=false]: verbose output
```

## Subcommands

* [eris data exec](https://docs.erisindustries.com/documentation/eris-cli/0.10.3/eris_data_exec/)	 - Run a command or interactive shell in a data container
* [eris data export](https://docs.erisindustries.com/documentation/eris-cli/0.10.3/eris_data_export/)	 - Export a named data container's volumes to ~/.eris/data/name
* [eris data import](https://docs.erisindustries.com/documentation/eris-cli/0.10.3/eris_data_import/)	 - Import ~/.eris/data/name folder to a named data container
* [eris data inspect](https://docs.erisindustries.com/documentation/eris-cli/0.10.3/eris_data_inspect/)	 - Machine readable details.
* [eris data ls](https://docs.erisindustries.com/documentation/eris-cli/0.10.3/eris_data_ls/)	 - List the data containers eris manages for you
* [eris data rename](https://docs.erisindustries.com/documentation/eris-cli/0.10.3/eris_data_rename/)	 - Rename a data container
* [eris data rm](https://docs.erisindustries.com/documentation/eris-cli/0.10.3/eris_data_rm/)	 - Remove a data container

## See Also

* [eris](https://docs.erisindustries.com/documentation/eris-cli/0.10.3/eris/)	 - The Blockchain Application Platform

## Specifications

* [Actions Specification](https://docs.erisindustries.com/documentation/eris-cli/0.10.3/actions_specification/)
* [Chains Specification](https://docs.erisindustries.com/documentation/eris-cli/0.10.3/chains_specification/)
* [Contracts Specification](https://docs.erisindustries.com/documentation/eris-cli/0.10.3/contracts_specification/)
* [Motivation](https://docs.erisindustries.com/documentation/eris-cli/0.10.3/motivation/)
* [Services Specification](https://docs.erisindustries.com/documentation/eris-cli/0.10.3/services_specification/)

