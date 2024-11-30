# ModCreationTool

### Description

A simple command line tool to assist in the creation of Stormworks mods, This tool will create the mod file structure for you.

### Usage:

Simply just open a command prompt in the location of the exe and run it with the name of the mod you are creating

### Example:

```bash
    C:\Users\Hello\Tools>ModCreationTool.exe test-mod
    Mod created at: C:/Users/Hello/Appdata/Roaming/Stormworks/data/mods/test-mod
```

The command will create something like this:

```
Stormworks/
`-- data/
    `-- mods/
        `-- my_mod/
            |-- audio/
            |-- data/
            |-- graphics/
            |-- meshes/
            |-- mod.png
            `-- mod.xml
```

Dont forget to customize mod.xml!
