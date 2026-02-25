## mcp-server-for-revit

English | [简体中文](README_zh.md)

mcp-server-for-revit is a framework that implements the mcp protocol based on Autodesk Revit software. It allows AI conversation clients compatible with the mcp protocol to drive Revit.

### Example

[ColorSplash](https://www.youtube.com/watch?v=mUJGSjQHBm8)

### Project Components

🔴

> [!WARNING]
> Deprecation notice, this repo is being archived in favour of the mono repo approch for the mcp https://github.com/mcp-servers-for-revit/mcp-servers-for-revit
> Simpler CI, less confusion for noobs, npm package and simpler install


---
---

These repo are deprecated in favour of https://github.com/mcp-servers-for-revit/mcp-servers-for-revit (monorepo)


The project consists of three main parts:

[**revit-mcp**](https://github.com/revit-mcp/revit-mcp): Connects with AI conversation clients. Responsible for providing executable functions to the AI conversation client and communicating with Revit.

[**revit-mcp-plugin**](https://github.com/revit-mcp/revit-mcp-plugin): This is a Revit plugin used to receive AI commands, load command sets, and execute specific functions.

[**revit-mcp-commandset**](https://github.com/revit-mcp/revit-mcp-commandset): Command sets are actual executable commands wrapped based on Revit external events. Developers can add functionality to the command set or customize their own work sets.

### Installation and Usage

You can learn how to install and use the project here: [Driving Revit through MCP](https://github.com/revit-mcp/revit-mcp-plugin/wiki/Driving-Revit-through-MCP)

### Join Us

You can contact us through [Discord](https://discord.gg/EYZFN9Xb4J) or [QQ Group](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=kLnQiFVtYBytHm7R58KFoocd3mzU_9DR&authKey=fyXDOBmXP7FMkXAWjddWZumblxKJH7ZycYyLp40At3t9%2FOfSZyVO7zyYgIROgSHF&noverify=0&group_code=792379482). We look forward to building the project together with you.

**Enjoy your journey!**
