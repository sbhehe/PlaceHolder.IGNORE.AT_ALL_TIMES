## Offline viewing sample for view and data API
This is a viewer running local files. See [Demo](http://developer-autodesk.github.io/viewer-javascript-offline.sample) here.

## Setup
To replace the file to be viewed, change the value of `document` in `index.html`.
````javascript
var options = {
    'document' : './shaver/0.svf',
    'env':'Local'
    };
````

Here are a few models you can use, just replace the `'document'` value with the url provided:


__Shaver__
````
http://developer-autodesk.github.io/translated-models/shaver/0.svf
````
![](http://developer-autodesk.github.io/view.and.data-javascript-offline.sample/shaver.png)


__House__
```
http://developer-autodesk.github.io/translated-models/dwfx-sample-house/f0224dd3-8767-45c1-ff99-5c9c881b9fee/0.svf
```
![](http://developer-autodesk.github.io/view.and.data-javascript-offline.sample/house.png)

You can also download those translated models from this [GitHub repo](https://github.com/Developer-Autodesk/translated-models).

You can translate your own models at [extract.autodesk.io](http://extract.autodesk.io).

## Written By
Shiya Luo
