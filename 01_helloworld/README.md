# Go Tutorial: Hello World

## 1. Hello World

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello World")
}
```

## 2. Run

```bash
go run main.go
```

## 3. Build

```bash
go build main.go
```

## 4. Run binary

```bash
./main
```

## 5. Install

```bash
go install
```

## 6. Run installed binary

```bash
01_helloworld
```

## 7. Cross compile

```bash
GOOS=linux GOARCH=amd64 go build main.go
```

## 8. Run cross compiled binary

```bash
./main
```

## 9. Install cross compiled binary

```bash
GOOS=linux GOARCH=amd64 go install
```

## 10. Test

```bash
go test
```


