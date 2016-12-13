# Sample for echo.go

app.go

# installing go in Mac OX X
brew install go

edit ~/.zshrc
```
export GOROOT=/usr/local/opt/go/libexec
export GOPATH=$HOME/go
export PATH=$PATH:$GOROOT/bin/:$GOPATH/bin
```

go get github.com/labstack/echo
