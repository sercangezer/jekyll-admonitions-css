# jekyll-admonitions-css

* add main style sheets

```scss
@import "_admonition";
```

* move the icons `/assets/img/icons` folder 


## Usage
```
{% include admonition.html type="info" title="Info" body="This is information intended to draw attention.<br/>This is information intended to draw attention. " %}

{% include admonition.html type="bug" title="Bug" body="This is information intended to draw attention." %}

{% include admonition.html type="abstract" title="Abstract" body="This is information intended to draw attention." %}

{% include admonition.html type="danger" title="Danger" body="This is information intended to draw attention." %}

{% include admonition.html type="example" title="Example" body="This is information intended to draw attention." %}

{% include admonition.html type="note" title="Note" body="This is information intended to draw attention." %}

{% include admonition.html type="question" title="Question" body="This is information intended to draw attention." %}

{% include admonition.html type="quote" title="Quote" body="This is information intended to draw attention." %}

{% include admonition.html type="tip" title="Tip" body="This is information intended to draw attention." %}

{% include admonition.html type="success" title="Success" body="This is information intended to draw attention." %}

{% include admonition.html type="warning" title="Warning" body="This is information intended to draw attention." %}
```

Thanks [Adamsdesk](https://www.adamsdesk.com/posts/admonitions-jekyll/)