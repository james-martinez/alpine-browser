# alpine-browser
![Github Docker Image CI](https://github.com/james-martinez/alpine-browser/workflows/Github%20Docker%20Image%20CI/badge.svg)

Currenly used with vnc at port 5900
password: 4321

### chromium with vnc
```
docker run -p 8000:5900 --shm-size 2g ghcr.io/james-martinez/alpine-browser/chromium:latest
```
run your vnc client and connecto to `localhost:8000`
