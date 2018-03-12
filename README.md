# singularity-docker-alpine-ctfr
singularity recipe for bootstrapping a ctfr container from a alpine:3.7 docker image (31 MB)
details at https://github.com/UnaPibaGeek/ctfr


```
sudo singularity build singularity-docker-alpine-ctfr Singularity
```

Using it:
```
./singularity-docker-alpine-ctfr -d facebook.com
```

Using without installing:
```
singularity run shub://truatpasteurdotfr/singularity-docker-alpine-ctfr  -d facebook.com
```
