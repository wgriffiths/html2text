[![GoDoc](https://godoc.org/github.com/k3a/html2text?status.svg)](https://godoc.org/github.com/k3a/html2text)
[![Build Status](https://travis-ci.org/k3a/html2text.svg?branch=master)](https://travis-ci.org/k3a/html2text)
[![Coverage Status](https://coveralls.io/repos/k3a/html2text/badge.svg?branch=master&service=github)](https://coveralls.io/github/k3a/go-arg?branch=master)
[![Report Card](https://goreportcard.com/badge/github.com/k3a/html2text)](https://goreportcard.com/report/github.com/k3a/html2text)

# html2text

Simple Go package to convert HTML to plain text.

## Install
```bash
	go get github.com/k3a/html2text
```

## Usage

```go
	import "github.com/k3a/html2text"

	func main() {
		html := `<html><head><title>Good</title></head><body><strong>nice</strong> text</body>`
		
		plain := html2text.HTML2Text(html)
				  
		fmt.Println(plain)
	}

	/*
	Outputs:
	
		nice text
	*/

```

## License

MIT
