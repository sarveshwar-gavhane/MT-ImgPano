# MT-ImgPano

Panoroma viewer for image.

## Usage

#### #include js

```
<script src="../dist/imgPano.js"></script>
```

#### #config & init

```
var imgPano = new ImgPano({
    src:'../assets/images/campus.png',
    fov:105,
    render:'webGL' // css3d||webGL
	onError: function (msg) {

    },
    onUpdate: function (data) {

    }
});

imgPano.init();
```

## build

```
## build THREE.JS
gulp js // while you add THREE.JS plugins, run this.

## build ImgPano
webpack -w src/js/imgPano.js dist/imgPano.js
```

## License

The MIT License (MIT)

Copyright (c) 2015 [Magic Term](https://github.com/MT-Libraries) Libraries

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
