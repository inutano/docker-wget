# Dockerfile for wget

An ultra simple and lightweight wget container using alpine linux.

## Example

```
$ docker run -v `pwd`:/data inutano/wget:1.20.3-r1 wget "http://google.com/" -P /data
```

This is too small thus you may use "--no-check-certificate" for https connection.
