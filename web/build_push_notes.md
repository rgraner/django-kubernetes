## Build your container image locally

```
docker build -t registry.digitalocean.com/rgraner-k8s/django-k8s-web:latest -f Dockerfile .
```

## Push your container image
```
docker push registry.digitalocean.com/rgraner-k8s/django-k8s-web --all-tags
```

Naturally, for all these steps replace `registry.digitalocean.com/cfe-k8s/` with your container registry and `django-k8s` with whatever image name you want to give your Django project.