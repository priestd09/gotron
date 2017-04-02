# Gotron
A boilerplate for cross-platform golang desktop applications using electron as Gui.

## Run
**golang**, **nodejs** and **npm** should be available on your system.  

Install Electron globally

    npm install -g electron

Clone to your go workspace (e.g. go/src)

    git clone https://github.com/equanox/gotron

Use npm install script and start application using main.go
```
cd gotron
npm run install
go run main.go
```
Now you should see this

![Hello Gotron](https://raw.githubusercontent.com/equanox/gotron/master/doc/hello_gotron.png)


## Tasks
- [x] Basic js + webpack example
- [ ] Typscript example
- [ ] Elm example
- [ ] React example
- [ ] Vue.js example
- [ ] Electron appearance on OS
- [ ] Create executables for Win, MacOS, Linux
- [ ] Config for go-nodejs socket

## Frontend Development Workflow
Go to *ui/js/src/app.js* and replace line 6 with

    topic.innerHTML = 'Hello Frontend Workflow';

Then type in root dir

    npm run build
    go run main.go

Reload updated index.js using 'r' key.

# License
MIT  

Except Roboto (ui/js/src/Roboto-Light.ttf) which is licensed under Apache 2.0   
https://github.com/google/roboto
