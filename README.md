# HTTP Server from scratch

Built with ruby. It is not spec-compliant neither secure (yet?)

This was just a holiday toy project, following the screencast made by Destroy All Software.

### To run the server and access the link.txt file (curl):
`killall ruby; ./server.rb&; sleep 1; curl -v 'http://127.0.0.1:9000/link.txt'`

### To run the server and execute the executable rb file (curl) :
`killall ruby; ./server.rb&; sleep 1; curl -v 'http://127.0.0.1:9000/executable.rb'`

### To run the server and get a not found error (curl):
`killall ruby; ./server.rb&; sleep 1; curl -v 'http://127.0.0.1:9000/something_non_existant.html'`

### To run the server and access the link.txt file in the web browser:
`killall ruby; ./server.rb&; sleep 1; open 'http://127.0.0.1:9000/link.txt'`
