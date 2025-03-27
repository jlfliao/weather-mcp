# Instructions

This demo follows the quickstart instructions [here](https://modelcontextprotocol.io/quickstart/server).

# Claude Desktop Config

Note: If you are encountering issues with Claude connecting to the server, use this config rather than the one stated in the tutorial. Replace <USER> with your username.

```
{
  "mcpServers": {
    "weather": {
      "command": "/Users/<USER>/.local/bin/uv",
      "args": ["--directory", "/Users/<USER>/weather", "run", "weather.py"]
    }
  }
}

```
