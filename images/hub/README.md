# About this folder

The Dockerfile in this folder is built by
[chartpress](https://github.com/jupyterhub/chartpress#readme), using the
requirements.txt file. The requirements.txt file is updated based on the
unfrozen/requirements.txt file using [`pip-compile`](https://pip-tools.readthedocs.io).

## How to update requirements.txt

Use the "Run workflow" button at
https://github.com/jupyterhub/zero-to-jupyterhub-k8s/actions/workflows/watch-dependencies.yaml.
