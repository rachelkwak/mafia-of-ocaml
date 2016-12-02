# Mafia of OCaml

Tyler Ishikawa, Rachel Kwak, Michael Lucido, Irene (Euisun) Yoon

## Dependencies
Before running the client or server, please make sure you have the following
packages installed using opam:

* async
* cohttp
* ansiterminal
* yojson
* lwt

## Running The Server
The server can be run using the `make server` command. By default, the server
will run on port 3110.

## Running The Client
The client can be run using the `make client URL={URL}` command, where `{URL}`
is replaced with the URL or IP address of the server you wish to connect to.
If you're running the server on the same computer, this would be
`URL=localhost:3110`. If you would like to connect to the public server our team
set up, you can use the `make client-default` command.
