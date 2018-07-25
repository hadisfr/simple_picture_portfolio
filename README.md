Simple Picture Portfolio
===
a simple php picture portfolio  
a part of <http://hadisafari.ir>([source](https://gitlab.com/hadi_sfr/hadisafari.ir))

## Usage

Set `avatar`, `name`, and `defaultdir` in _index.php_. Then put pictures in a proper folder structure:

    dir/file.png
    dir/thumb/file.png
    dir/det.js (optional)

While _det.js_ should be in the following format:
```js
{
    "file.png": "detail",
    "anotherfile.png": "det"
};
```
