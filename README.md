# A Simple (Testing container signing) Skaffold Env!
A basic development environment powered by Skaffold (for use as a testing environment). Running a multi-service PERN application as the AUT.

Development requirements :
- Docker Desktop (Windows install) v24.0.2
- Kubernetes Clusters on v1.27.2
    - Need to have ingress-nginx installed!
- Skaffold (Linux install) v2.6.0

After ensuring the above dependecies are installed, clone the repository and cd into the root.

Run skaffold dev - ctrl+c to teardown env - enjoy :D.
