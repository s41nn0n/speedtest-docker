# Speedtest
docker image hosting the speedtest cli for easy and quick speed tests

This is a docker build file to host the [speedtest](https://www.speedtest.net/apps/cli) cli

# Use
```
git clone https://github.com/team142/speedtest-docker.git
cd speedtest-docker
docker build -t speedtest/speedtestcli:latest -f ./Dockerfile .
docker run speedtestcli:latest speedtest -p no
```
