# wails-to-wasm-app

This repository is designed to make a web page available that is uses source code that is based on source code (go, html, css) from the [Hello World tutorial](https://wails.io/docs/tutorials/helloworld) and that uses webAssembly(wasm) technology. It is based on an approach outlined in [this tutorial](https://golangbot.com/webassembly-using-go/) and [it's subsequent tutorial](https://golangbot.com/go-webassembly-dom-access/). The source used can be found in (this repository)[https://github.com/tataDan/wails-to-wasm/].

## Steps taken to create this repository and web page

I copied all the files from the frontend directory from the (above mentioned repository)[https://github.com/tataDan/wails-to-wasm/]. Note: I copied the files contained in that directory not the directory itself.

I changed this line 

```<img id="logo" class="logo" src="../assets/images/logo-universal.png">```

 to ```<img id="logo" class="logo" src="assets/images/logo-universal.png">```.

This was necessary because in the original source code the html.index file is in the frontend directory, but that is not the case here. (Note: I could have chosen to have all the files in the project level directory of the original source code instead of in the frontend directory).

I then went to Settings/Pages and chose ```main``` for the branch.  After a short period of time, (this site)[https://tatadan.github.io/wails-to-wasm-app/] was created.

## Closing thought

I chose to use GitHub Pages because it was quick and easy. In many cases using a web hosting site or deploying the site using a private web server would be more appropriate.
