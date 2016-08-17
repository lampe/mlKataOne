# mlKataOne

# Api calls

```bash
#rock
curl -H "Content-Type: application/json" -X POST -d '{"move":"rock"}' http://localhost:3000/api/move
#paper
curl -H "Content-Type: application/json" -X POST -d '{"move":"paper"}' http://localhost:3000/api/move
#scissors
curl -H "Content-Type: application/json" -X POST -d '{"move":"scissors"}' http://localhost:3000/api/move
