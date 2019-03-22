# Comp_health
General diagnostic commands

This is a list of useful commands to find information about a system, including hardware and software status. Commands are aggregated from various internet sources.

system_profiler

The system_profiler command is a command line interface (CLI) to the System Profiler application that every Mac comes with. This command is useful in situations where it is necessary to probe a machine that you don’t have permissions to access a GUI.
DETAILLEVEL
The system_profiler command offers three different levels of reports: mini, basic, and full.

system_profiler -detailLevel mini: This will generate a text report of information from System Profiler without any personal or identifying information.
system_profiler -detailLevel basic: This command generates the report with only the basic hardware and network information.
system_profiler -detailLevel full: Generates a report with all of the available information from System Profiler.

This is the one you generally want. Outputs hardware on system

$ system_profiler SPHardwareDataType
