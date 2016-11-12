# paper-tree

Display a browsable tree of nodes (`<paper-tree-node>`) with expandable/collapsible capabilities and actions menu for each node.

Each node is defined by a **name**, an **icon**, an **open** state (expanded/collapsed) and an **actions** menu.

Example:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-tree.html">
  </template>
</custom-element-demo>
```
-->
```html
<paper-tree data='{
    "name": "GOT",
    "icon": "theaters",
    "open": true,
    "children": [{
        "name": "Starks",
        "icon": "turned-in",
        "children": [{
            "icon": "account-circle",
            "name": "Eddard"
        }, {
            "name": "Catelyn",
            "icon": "account-circle"
        }, {
            "name": "Sansa",
            "icon": "account-circle"
        }, {
            "name": "Robb",
            "icon": "account-circle"
        }, {
            "name": "Bran",
            "icon": "account-circle"
        }, {
            "name": "Arya",
            "icon": "account-circle"
        }, {
            "name": "Rickson",
            "icon": "account-circle"
        }]
    }]}'>
 </paper-tree>
```

## Installation

First, make sure you have [Bower](https://bower.io/) and the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed.

Then,

```
bower install
polymer serve -o
```

## Usage

Add a `<paper-tree>` element to your page and set the `data` attribute:

```
<paper-tree data='{"name": "root"}'><paper-tree>
```

See documentation to know the options and structure of the `data` attribute.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* **1.0:** initial release.

## License

MIT license
