# TelnetServer

This is a DOTNET core port of the C# TelnetServer.
Credits go to UngarMax (https://github.com/UngarMax/TelnetServer)

# Usage

* Start the TelnetServer

`dotnet run`

The demo uses telnet-user `root` with password `r00t`. Other users not allowd to login.

* Start two telnet clients (with putty or the linux/windows telnet command)

`telnet localhost`

When the TelnetServer prompt is displayed, login with user root.

Type a text line. The line is received by the TelnetServer and echoed in the console.

* Send a TelnetServer text-line to all telnet-clients

In the TelnetServer session, type character `b` followed by a line of text.

The message should appear in client sessions.

* Client commands

`exit `to exit the telnet client.
