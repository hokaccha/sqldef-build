```
$ docker build -t sqldef . --build-arg VERSION=$BRANCH_NAME --platform linux/amd64
$ docker run --name sqldef --rm -it sqldef /bin/bash
$ docker cp sqldef:/sqldef/build/linux-amd64/psqldef .
```
