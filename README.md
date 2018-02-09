# docker-pipe-log-output-to-stdout-with-docker
 How to append output to STDOUT, and how to view log output from your running containers.

## Commands

1. docker  build -t foo .
2. docker run -d --name=foo foo
3. docker logs -f foo
4. docker exec -it foo cat /debug.log
