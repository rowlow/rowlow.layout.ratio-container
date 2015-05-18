# rowlow.layout.ratio-container

A module for creating DOM container with a defined aspect ratio. Preconfigured ratios are 1by1, 4by3, 16by9 and 21by9, but can be extended upon your needs.

## Install

```
    bower install --save rowlow.layout.ratio-container
```


## Settings

```
    rowlow-ratio-container-namespace // Specific module namespace
    rowlow-ratios // List of ratios
```

## Usage

### SCSS

```
    /* Set modules namespace (optional) */
    $rowlow-ratio-container-namespace: "namespace-";

    /* Overwrite ratio list (optional) */
    $rowlow-ratios: (
        (1,1),
        (4,3),
        (16,9),
        (21,9)
    )

    @import "bower_components/rowlow.layout.ratio-container/main.scss"
```

### HTML

```
    <div class="ratio-block--s--21by9 ratio-block--l--16by9"></div> 
```