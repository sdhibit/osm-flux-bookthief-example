# osm-flux-bookthief-example
Open Service Mesh Bookthief example for use with fluxcd


# Install OSM CLI
```bash
brew install osm
```

# Watch namespaces in OSM
```bash
osm namespace add bookstore bookbuyer bookthief bookwarehouse
```


https://github.com/openservicemesh/osm/blob/main/charts/osm/templates/mutatingwebhook.yaml#L19
https://github.com/openservicemesh/osm/blob/main/docs/content/docs/onboard_services.md

https://www.digitalocean.com/community/tutorials/how-to-manage-your-kubernetes-configurations-with-kustomize
https://github.com/kubernetes-sigs/kustomize/tree/master/examples