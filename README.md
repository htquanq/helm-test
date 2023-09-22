# This repository will be helm-library to generate manifest files which will be applied to kubernetes cluster

# Result can be view in rendered folder

# Edit values.yaml and run command below to get the result

```bash
rm -f charts/*.tgz
helm dep up
helm template . --output-dir rendered
```