# Charts Repo

Example charts repository

GitHub Pages to point to the docs folder.

```console
$ helm create nginx-ingress
$ helm package nginx-ingress
$ mv nginx-ingress-0.23.0.tgz docs
$ helm repo index docs --url https://panho66.github.io/helm-chart/
$ git commit -a -m 'add nginx-ingress'
$ git push origin master
```

helm repo add laputa https://panho66.github.io/helm-chart/
 
