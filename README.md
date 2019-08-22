# nunjucks-vscode-snippets 

A tight and simple collection of usefull nunjucks snippets

## Usages

![Usage](images/usage.gif)

### Snippets

| Prefix      | HTML Snippet Content                             |
| ----------- | ------------------------------------------------ |
| `var`       | `{{ variable }}`                                 |
| `extends`   | `{% extends "template" %}`                       |
| `include`   | `{% include "template" %}`                       |
| `inject`    | `{% inject "template" %}`                        |
| `for`       | `{% for item in content %} {% endfor %}`         |
| `if`        | `{% if condition %} {% endif %}`                 |
| `ife`       | `if else`                                        |
| `ifel`      | `if elif`                                        |
| `elif`      | `elif`                                           |
| `else`      | `else`                                           |

**bdt**

```html
{{bodytext | safe}}
```

**link** 

```html
<a href="{{ item.href.value }}" {% if item.href.target %}target="{{ item.href.target | default('_blank') }}"{% endif %}>{{ item.label }}</a>
```

**row**

```html
<div class="row">
	<div class="column"></div>
	<div class="column"></div>
</div>
```