# Accelerator Log

## Options
```json
{
  "branch" : "main",
  "name" : "simple-tanzu-accelerator",
  "projectDescription" : "",
  "projectName" : "Simple Tanzu Accelerator",
  "tags" : [ "example" ],
  "url" : "https://github.com/ppringle/simple-tanzu-accelerator"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Combo, UniquePath)
┃ ┏ engine.transformations[0] (Combo)
┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ engine.transformations[0].merge (Chain)
┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┏ engine.transformations[0].merge.transformations[0] (Merge)
┃ ┃ ┃  Info Running Merge(YTT, Combo)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0] (YTT)
┃ ┃ ┃ ┗ Debug Wrote values file with json content:   {"artifactVersion":"0.0.1-beta","name":"simple-tanzu-accelerator","projectDescription":"","icon":"https://raw.githubusercontent.com/simple-starters/icons/master/icon-tanzu-light.png","artifactId":"Simple_Tanzu_Accelerator","projectName":"Simple Tanzu Accelerator","branch":"main","url":"https://github.com/ppringle/simple-tanzu-accelerator","tags":["example"]}
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[1].include (Include)
┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ Debug new-accelerator.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┗ ┗ Debug k8s-resource.yaml didn't match [README.md] -> excluded
┃ ┗ ╺ engine.transformations[0].merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
