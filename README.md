# History

## 2020-08-12T18:21:07+02:00@Europe/Paris — How to setup local channel

- [sublimetext3 - Using Package control with an offline repo - Stack Overflow](https://stackoverflow.com/questions/50650268/using-package-control-with-an-offline-repo)
- [How to create an https server? &vert; Node.js](https://nodejs.org/en/knowledge/HTTP/servers/how-to-create-a-HTTPS-server/)
- [ST3(3126): Package Control SSL Cert Invalid Errors, reinstall didn't help - Technical Support - Sublime Forum](https://forum.sublimetext.com/t/st3-3126-package-control-ssl-cert-invalid-errors-reinstall-didnt-help/23539/7)





# Installation

## Sublime Text

- make sure to uninstall any previously installed version
- push all the wanted changes to `master`
- start local server with `server.bat`
- make sure channel is added: `http://127.0.0.1:8080/channel.json`
- make sure it is first, if not remove and add again: `https://packagecontrol.io/channel_v3.json`

## Visual Studio Code

- `build_for_vscode.bat`
- `codium --install-extension livescript-0.1.1.vsix` or `code --install-extension livescript-0.1.1.vsix`: adapt package name. Can also be done manually in the software
