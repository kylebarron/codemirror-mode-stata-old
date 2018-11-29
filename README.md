# codemirror-mode-stata
> A CodeMirror mode for Stata

## Installation

```console
npm install codemirror codemirror-mode-stata --save
```

## Usage

1. Include `codemirror-mode-stata` into your project.

    ```html
    <!-- You can simply add stata.js as a script tag: -->
    <script src="js/codemirror.js"></script>
    <script src="js/codemirror-mode-stata/dist/stata.js"></script>
    ```

2. Set 'stata' as the mode when creating the CodeMirror editor.

    ```js
    CodeMirror.fromTextArea(document.getElementById('code'), { mode: 'stata' })
    ```

## License

MIT - See [LICENSE](https://github.com/kylebarron/codemirror-mode-stata/blob/master/LICENSE)
