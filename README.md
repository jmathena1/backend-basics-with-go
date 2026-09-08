This repo is me following the tutorial on backend web development written by Efron Licht.

You can find this is series and the rest of Efron's writing [here](https://eblog.fly.dev/index.html#:~:text=backend%20from%20the%20beginning%3A%20a%20complete%20guide%20to%20backend%20development%20in%20go)

## Running this tiny server
Execute the commands below to have a local mini server that does nothing but uppercase strings

1. `go build -o tcpupperecho ./tcpupperecho.go`
2. `./tcpupperecho -p 8080 # run the server, listening on port 8080`
3. In a new terminal: `go build -o writetcp ./writetcp.go`
4. `./writetcp -p 8080`
5. Now type stuff and see it big! woooo
