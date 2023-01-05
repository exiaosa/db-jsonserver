# Setup
## Install
install: `npm install -g json-server`

cretae a folder (e.g. db), and then create a json file in it (e.g. db.json)

## run
Inside db folder, run ` json-server --watch .\src\db.json --port 3004`

Visit http://localhost:3004/xxx (xxx is the name of the json objects in the db.json)

## json-server is not allowed
In PowerShell type: `set-ExecutionPolicy remoteSigned`

Then type: `Y`