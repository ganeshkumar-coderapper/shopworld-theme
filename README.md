# shopworld-theme

shopify theme customized from dawn theme to feature custom developed masonry styled dynamic lookbook section


## Media Masonry - section
- to dynamically implement masonry tile styled lookbook with responsive ui
- library dependency - jquery


### tiles types
- simple image
- image with onclick embedded video popup 
- image with onhover VIEW and ADD TO CART button


### tile type logic
- for each tile, image selection is mandatory
- if no video_url provided or product selected for the tile, simple image tile will be shown
- if video_url provided, image tile with onclick video popup will be shown
- if product selected, image tile with onhover VIEW button and ADD TO CART button will be shown


### add to cart button with ajax
- ADD TO CART click will add the product to cart using ajax
- validation in rule to prevent recursively adding same product to cart from lookbook view


## files
```
├── assets
│   ├── gen-style.css
│   └── gen-script.js
│
├── layout
│   └── theme.liquid
│
├── sections
│   └── media-masonry.liquid
│
└── snippets
    └── popup-vdo.liquid
```
