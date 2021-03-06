# ExaNIC Debug Dump

The ExaNIC Debug Dump is a Python script that creates a gunzipped logfile containing useful debug information used to troubleshoot Exablaze ExaNIC devices.

## Quick Start

You can create a debug dump using the following command:

```
curl https://raw.githubusercontent.com/exablaze-oss/exanic-debug-dump/master/exanic_debug_dump.py | python
```

The script will state the absolute filepath of the resulting debug dump. Upload this debug dump to the Cisco TAC support case for further review.

## Supported Python Versions

This script can be run using Python 2 or Python 3.

## Versioning

This script implements [SemVer](https://semver.org/).

## License

This project is licensed under the GPLv2 license. See the [LICENSE](https://github.com/exablaze-oss/exanic-debug-dump/blob/master/LICENSE) file for details.
