Have sample docker container written in python.

The port of container 4000 fowards to port 4000 of host.

In docker-compose.yml port 4000 of containers will be forwarded to 80 of host.

docker stack deploy -c docker-compose.yml test_swarm

This is the swarm in local machine, you can build your vms to build swarm(master and worker)
