- Add a link to correct folders (lib) 
 - Windows: `mklink Link(full_path) Target (full_path)`
 - e.g. `mklink /D .\aware-client\com.aware.plugin.mwt\com.aware.plugin.mwt.lib\src .\aware-client\com.aware.plugin.mwt\com.aware.plugin.mwt\src`

- To update the `mwt` brnch use;
 - `git submodule update --remote`