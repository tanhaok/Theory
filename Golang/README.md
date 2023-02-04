
# GO LANG
> All code and theory learned accordingly this [roadmap](https://roadmap.sh/golang)
---
## 0. Overview of Go Programming Language
### What is Go?
- Go is a cross-platform, open source language.
- Go can be used for create high-performance applications.
- Go is fast, statically type, compiled language, interpreted language.
- Go's syntax is similar to C++.

### What is Go used for?
- Web Development (Server Side)
- Developing network-base programs.
- Cloud native development.
- Develop cross-platform enterprise application

### Why use Go?
- Go is fast and easy to learn.
- Go works on cross-platform such as Linux, window, Raspberry PI, MacOS...
- Go has runtime and compilation time
- Go has memory management.

### Compare Go with C++ and Python
| Go | C++ | Python |
| --- | --- | --- |
| Has automatic Garbage Collection | Doesn't have | Has automatic Garbage Collection |
| Compiled | Interpreted | Compiled |
| Statically Type | Statically Type | Dynamic Type |
| Fast run time | Fast run time | Slow run time |
| Fast Compiled Time | Interpreted | Slow Compiled Time |
| Doesn't support class and object | Have object and class | Have object and class |
| Doesn't support inheritance | Support inheritance | Support inheritance |


## 1. Basic Syntax
### 1.1. Simple Hello World Program.
1. First of all run ```go mod init Code/hello``` to enable dependency tracking code
1. Create a file `hello.go` and fill with following code belo 
```go
package main

import "fmt"

func main () {
    fmt.Println("Hello World!")
}
```
3. Open terminal and type:

> go run .

4. Now if want to save executable type and run:
> go build .