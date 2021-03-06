---
filename: /packages/material-ui/src/CardActions/CardActions.js
title: CardActions API
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# CardActions

<p class="description">The API documentation of the CardActions React component. Learn more about the properties and the CSS customization points.</p>

```js
import CardActions from '@material-ui/core/CardActions';
```



## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span class="prop-name">children</span> | <span class="prop-type">node |   | The content of the component. |
| <span class="prop-name">classes</span> | <span class="prop-type">object |   | Override or extend the styles applied to the component. See [CSS API](#css-api) below for more details. |
| <span class="prop-name">disableActionSpacing</span> | <span class="prop-type">bool | <span class="prop-default">false</span> | If `true`, the card actions do not have additional margin. |

Any other properties supplied will be spread to the root element (native element).

## CSS API

You can override all the class names injected by Material-UI thanks to the `classes` property.
This property accepts the following keys:


| Name | Description |
|:-----|:------------|
| <span class="prop-name">root</span> | Styles applied to the root element.
| <span class="prop-name">action</span> | Styles applied to the children.

Have a look at [overriding with classes](/customization/overrides/#overriding-with-classes) section
and the [implementation of the component](https://github.com/mui-org/material-ui/tree/master/packages/material-ui/src/CardActions/CardActions.js)
for more detail.

If using the `overrides` key of the theme as documented
[here](/customization/themes#customizing-all-instances-of-a-component-type),
you need to use the following style sheet name: `MuiCardActions`.

## Demos

- [Cards](/demos/cards/)

