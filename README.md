Mechanical M-Ayhem FMS 2025
============
Field Management System for Team 766's Mechanical M-Ayhem rookie competition for the 2025 season.
Forked from [Mechanical M-Ayhem FMS Generic](https://github.com/Team766/mayhem-fms-generic), which itself is a fork from
[Team 254's Cheesy Arena](https://github.com/Team254/cheesy-arena).

This repo contains scoring logic, scorer and ref panels, audience display that is updated for Mechanical M-Ayhem 2025.

## Installing

**From source**

1. Download [Go](https://golang.org/dl/) (version 1.22 or later required)
1. Clone this GitHub repository to a location of your choice
1. Navigate to the repository's directory in the terminal
1. Compile the code with `go build`
1. Run the `cheesy-arena` or `cheesy-arena.exe` binary
1. Navigate to http://localhost:8080 in your browser (Google Chrome recommended)

**IP address configuration**

When running Cheesy Arena on a playing field with robots, set the IP address of the computer running Cheesy Arena to
10.0.100.5. By a convention baked into the FRC Driver Station software, driver stations will broadcast their presence on
the network to this hardcoded address so that the FMS does not need to discover them by some other method.

When running Cheesy Arena without robots for testing or development, any IP address can be used.
