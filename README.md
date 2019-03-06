### go-callvis
---
https://github.com/TrueFurby/go-callvis

```go
func CanHaveDynamicTypes(T types.Type) bool

func CanPoint(T types.Type) bool

type Config struct {
  Mains []*ssa.Package
  
  Reflection bool
  
  BuildCallGraph bool
  
  Queries map[ssa.Value]struct{}
  IndirectQueries map[ssa.Value]struct{}
  
  Log io.Writer
}

c.AddExtendedQuery(v, "x[1][0].F")


type Result struct {
  CallGraph *callgraph.Graph
  Queries map[ssa.Value]Pointer
  IndirectQueries map[ssa.Value]Pointer
  Warning s []Warngng
}

```

```
go get -u github.com/TrueFurby/go-callvis
cd $GOPATH/src/github.com/TrueFurby/go-callvis && make
```

```
```


