# K8s charts

#### Create a Chart
```
helm create <chart>
```

#### Lint
```
helm lint ./<chart>
```

#### Template
```
helm template ./<chart>
```

#### Install
```
helm install --name <chart> ./<chart>
```

#### List
```
helm ls --all
```

#### Upgrade
```
helm upgrade <char> ./<chart>
```

#### Rollback
```
helm rollback <chart> 1
```

#### Uninstall
```
helm uninstall <chart>
```

#### Search
```
helm search repo <keyword>
```

### Repository
#### Configuration
GitHub Pages

Create branch *gh-pages* and set it as a default branch

#### Package
```
helm package <chart> -d charts
```

#### Index
```
helm repo index charts
```