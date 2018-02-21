Skeleton theme
============

The Skeleton theme is a simplified Virto Commerce theme adopted from Shopify theme using the same name, to be used as a "blank slate" starting point for theme designers.

<b>Features:</b>
- Almost no theme settings. Ready to be customized any way you want. 
- Only ~500 lines of CSS including comments. 
- Despite its 500 lines of CSS code, it is responsive and has styled drop-down menus.
- Include SVG images to style select elements and cart icon.
- Commented code to teach you Liquid concepts in practice.

![skeleton-catalog](https://user-images.githubusercontent.com/10347112/36481375-4f3a484c-1718-11e8-8595-7bd1f1184338.png)
![skeleton-product-1](https://user-images.githubusercontent.com/10347112/36481376-4f5aef34-1718-11e8-9b82-e8deb352656c.png)

Getting started
---------------------
1. <a href="https://github.com/virtocommerce/skeleton-theme/archive/master.zip">Download</a> the latest version
2. or clone the git repo: <code>git clone https://github.com/virtocommerce/skeleton-theme.git</code>

Basic structure
---------------
```
├── assets
│   └── Javascript, CSS, and theme images
├── config
│   └── custom Theme Settings
├── layout
│   ├── theme.liquid
│   └── optional alternate layouts
├── snippets
│   └── optional custom code snippets
├── templates
|   └── customers
|       ├── login.liquid
|       └── register.liquid
│   ├── 404.liquid
│   ├── article.liquid
│   ├── blog.liquid
│   ├── cart.liquid
│   ├── collection.liquid
│   ├── index.liquid
│   ├── page.liquid
│   ├── product.liquid
│   └── search.liquid
│   └── list-collections.liquid
```

Additional resources
---------------------
- <a href="http://docs.virtocommerce.com">Documentation</a>: Learn more about Liquid and theme templates.
