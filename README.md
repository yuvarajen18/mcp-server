{
  "mcpServers": {
    "Weather": {
      "command": "C:\\Users\\ko160f5\\.local\\bin\\uv.EXE",
      "args": [
        "run",
        "--with",
        "mcp[cli],pyautogui",
        "mcp",
        "run",
        "C:\\Users\\ko160f5\\Music\\agentai\\weather.py"
      ]
    },
    "Crypto": {
      "command": "C:\\Users\\ko160f5\\.local\\bin\\uv.EXE",
      "args": [
        "run",
        "--with",
        "mcp[cli],requests",
        "mcp",
        "run",
        "C:\\Users\\ko160f5\\Music\\agentai\\crypto.py"
      ]
    },
    "Prompt": {
      "command": "C:\\Users\\ko160f5\\.local\\bin\\uv.EXE",
      "args": [
        "run",
        "--with",
        "mcp[cli]",
        "mcp",
        "run",
        "C:\\Users\\ko160f5\\Music\\agentai\\prompt.py"
      ]
    },
    "Resources": {
      "command": "C:\\Users\\ko160f5\\.local\\bin\\uv.EXE",
      "args": [
        "run",
        "--with",
        "mcp[cli]",
        "mcp",
        "run",
        "C:\\Users\\ko160f5\\Music\\agentai\\resources.py"
      ]
    },
     "add_number": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/yuvarajen18/mcp-server.git",
        "mcp-server"
        
      ]
    }
  }
}