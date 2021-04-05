# pyright_beam_weirdness
To create the docker image,

```docker build -t beam_import -f Dockerfile .```

Then do 

```
docker run -it beam_import bash
pyright beam_weirdness.py
```

This should show no errors, but currently has 1 error message of

```
"Sample" is not a known member of module
```
