# Personal Service Tools

Small Linux user services from a personal workstation. These are source and service configurations, not a ready-to-run installer.

- `clipboard/`: watches the X11 clipboard and converts BMP images to PNG when PNG is unavailable. Requires `xclip`, ImageMagick `convert`, and `notify-send`.
- `dingtalk-calendar/`: a DingTalk event-consumer service configuration. It buffers messages for a personal calendar workflow; it does not itself create calendar events. The event-processing automation is paused. Requires the configured `dws` CLI and local directories.

Service paths and dependencies must be adapted to the target machine. This repository contains no message inbox, account credentials, calendar data, or runtime state.
