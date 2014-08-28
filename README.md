IDX-Showcase-Custom-Examples
============================

#### Media Queries
> Please replace the {{widgetID}} by your widget ID

![](https://raw.githubusercontent.com/icharlie/IDX-Showcase-Custom-Examples/master/images/showcase.gif)


```css
@media (max-width: 768px) {
    #IDX-showcaseGallery-{{widgetID}} {margin: 0px !important;}
    #IDX-showcaseGallery-{{widgetID}} .IDX-showcaseCell {min-width: 100%;height: auto !important;}
    #IDX-showcaseGallery-{{widgetID}} .IDX-showcasePhoto {max-height: inherit !important;}
}
```
