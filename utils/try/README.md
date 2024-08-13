# Try-Finally-Catch

Common utils

### Usage

Quick usage
```go
import "github.com/vinhio/gfly-modules/utils/try"

try.Perform(func() {
    calledTry()
}).Finally(func() {
    calledFinally()
}).Catch(func(e try.E) {
    log.Errorf("Catch error %v", e)
})
```
