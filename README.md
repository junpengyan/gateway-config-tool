# Configuration tools

This repository contains separate Windows and macOS source packages for two local Python web tools.

| Tool | Windows | macOS |
| --- | --- | --- |
| Gateway configuration workbench | [ZIP](gateway-config-tool-v2/windows/gateway-config-tool-v2-windows.zip) | [ZIP](gateway-config-tool-v2/macos/gateway-config-tool-v2-macos.zip) |
| IO configuration tool | [ZIP](io-config-tool/windows/io-config-tool-windows.zip) | [ZIP](io-config-tool/macos/io-config-tool-macos.zip) |

Extract a package before use. Python 3.10+ is required. On Windows run `start.bat`; on macOS run `start.command` or `./start.sh`. These packages contain Python source, not standalone native executables.

Runtime data, saved plans, generated projects, logs, PID files, and credentials are excluded. `gateway-config-tool-v2` users must provide their own `db.xml` and CSV templates and set their paths after moving machines. The macOS packages have not been tested on a Mac.
