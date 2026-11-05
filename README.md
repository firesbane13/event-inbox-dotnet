# event-inbox-dotnet

A C# server, on .NET, that takes a device reading.

The same reading can arrive more than once. A network failure makes the sender try again. The goal is to take the retry and still apply that reading once. This folder runs on its own.
