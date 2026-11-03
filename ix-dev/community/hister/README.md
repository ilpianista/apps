# Hister

[Hister](https://hister.org) is a private search engine for the pages you visit and the files you keep. It indexes their full contents so you can find information again from the web interface, terminal, or an AI assistant connected through MCP.

The Web UI and browser extension require the Access Token configured for this app. Install the browser extension and set its server URL to the configured Base URL.

To index local files, mount the directories under Additional Storage, add their container paths under Directories to Index, and restart the app. Hister scans the directories at startup and watches them for changes. When Directories to Index is empty, you can provide a full Hister configuration at /hister/data/config.yml instead.

Use HTTPS through a reverse proxy when exposing Hister outside your local network.

For more information, see the [Hister documentation](https://hister.org/docs).
