# CodeMirror for Go

Polymer element wrapping [CodeMirror](http://codemirror.net), includes only the Go parser with the Material theme.

## What is this?
Code-Mirror is a Web Component made with [Polymer](https://www.polymer-project.org/) that wraps a default text-area with CodeMirror's highlight syntax, plugins and options.

## Installation and usage

#### Install with npm:
`npm i --save polymer-code-mirror`
#### Install with Bower
`bower install --save polymer-code-mirror`

In your html file import the component and just drop the tag.

```html
...
<head>
    <link rel="import" href="bower_components/polymer-code-mirror/code-mirror.html"/>
</head>
<body>
    <code-mirror mode="python" theme="solarized dark">
    import turtle

    t = turtle.Turtle()

    for c in ['red', 'green', 'yellow', 'blue', 'lime']:
        t.color(c)
        t.forward(72)
        t.left(72)
    </code-mirror>
</body>
```

`<code-mirror>` expects a *mode* (the language). If none is passed, the syntax highlight will not work.

## Contributing
Feel free to contribute by sending a PR.
