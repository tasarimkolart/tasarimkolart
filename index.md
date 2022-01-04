## 

You can use the [editor on GitHub](https://github.com/tasarimkolart/tasarimkolart/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/tasarimkolart/tasarimkolart/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
html,
body {
    margin: 0;
    padding: 0;
    width: 100%;
    height: 100%;
    font-family: sans-serif;
}

iframe {
    display: block;
    border: 0;
    width: 100%;
    height: 100%;
}

.app {
    display: flex;
    width: 100%;
    height: 100%;
}

#api-frame {
    flex: 1 1 auto;
}

.options {
    box-sizing: border-box;
    flex: 0 0 300px;
    padding: 30px;
    overflow: auto;
}

.option {
    display: flex;
    padding: 16px 0;
    border-bottom: 1px solid #ccc;
}

.option:first-child {
    border-top: 1px solid #ccc;
}

.option label {
    flex: 0 0 130px;
}

.color {
    display: flex;
    align-items: center;
    padding: 4px 0;
}

.color input[type='radio'] {
    position: absolute;
    opacity: 0;
    pointer-events: none;
}

.color__swatch {
    display: inline-block;
    width: 24px;
    height: 24px;
    border-radius: 50%;
    border: 1px solid rgba(0, 0, 0, 0.5);
    margin-right: 4px;
}

.color input:checked + .color__swatch {
    box-shadow: 0 0 0 2px #000;
}

.color:hover .color__swatch {
    box-shadow: 0 0 0 2px #999;
}

.texture {
    display: block;
    position: relative;
    margin-bottom: 10px;
}

.texture input[type='radio'] {
    position: absolute;
    opacity: 0;
    pointer-events: none;
}

.texture__preview {
    display: block;
    height: auto;
}

.texture input:checked + .texture__preview > img {
    box-shadow: 0 0 0 2px #000;,t,r){var n=r(116),a=r(0),o=r(65)("met
