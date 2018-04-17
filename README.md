# rivet-env
Print [Tcl](https://tcl.tk/) version and [Apache Rivet](https://tcl.apache.org/rivet/) env info

Use `info patchlevel` to get Tcl version, `::rivet::inspect server` to get server info,
and print env array info.

If users just want to print env array, Apache Rivet provides `::rivet::parray` command to print array.
