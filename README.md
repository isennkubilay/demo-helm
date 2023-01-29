1. `helm create kubi-webapp`
2. `cd kubi-webapp`
3. `helm template .`
4. `helm package cloudacademy-webapp`
5. `helm install demoapp kubi-webapp-0.1.0.tgz`
6. `helm ls`
7. `helm status demoapp`
8. `helm history demoapp`
9. `helm upgrade demoapp kubi-webapp-0.1.0.tgz --set nginx.conf.message="Helm Rocks"`
10. `helm rollback demoapp`
11. `helm uninstall demoapp`