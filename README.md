# Resource hints

Welcome! While my example pages focus on **preconnect**, there is also **prefetch**, **prerender**, **preload**, and **dns-prefetch**. Be sure to look them up as well.

## Implementation
You can use resource hints with the ```<link>``` tag. For example:
```html
<link rel="preconnect" href="//fonts.gstatic.com">
```

## Browser support

As these are relatively new techniques, browser support is not yet universal.
* [Preconnect](https://caniuse.com/#feat=link-rel-preconnect)
* [Prefetch](https://caniuse.com/#feat=link-rel-prefetch)
* [DNS-Prefetch](https://caniuse.com/#feat=link-dns-prefetch)
* [Prerender](https://caniuse.com/#feat=link-rel-prerender)
* [Preload](https://caniuse.com/#feat=link-rel-preload)

## Helpful tools/links
* [Webpagetest](https://www.webpagetest.org/)
* [Caniuse](https://caniuse.com/)
* [Spec for preconnect/prefetch/prerender/dns-prefetch](https://w3c.github.io/resource-hints/)
* [Spec for preload](https://www.w3.org/TR/preload/)
