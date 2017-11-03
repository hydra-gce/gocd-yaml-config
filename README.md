# gocd-yaml-config
GoCD configurations in YAML for Hydra

Install [GoCD YAML configuration plugin](https://github.com/tomzo/gocd-yaml-config-plugin) and add this to your XML config:
```xml
<config-repos>
  <config-repo plugin="yaml.config.plugin">
    <git url="https://github.com/hydra-gce/gocd-yaml-config.git" />
  </config-repo>
</config-repos>
```
