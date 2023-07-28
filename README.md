# Spryker Feature: Product Bundles

Tie individual items together and sell them as a package. Items in a bundle are always sold together. Apply a special bundle price to make the purchase more attractive. Bundle availability is calculated and displayed based on the item with the smallest available stock to avoid overselling.

[Learn more](https://docs.spryker.com/docs/pbc/all/product-information-management/202307.0/base-shop/feature-overviews/product-bundles-feature-overview.html)

## Installation

```
composer require spryker-feature/product-bundles
```

## Recommended feature dependencies
- [spryker-feature/product](https://github.com/spryker-feature/product)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [CartNoteProductBundleConnector ^1.1.0](https://github.com/spryker/cart-note-product-bundle-connector) (Connector)
- [ProductBundleCartsRestApi ^1.0.0](https://github.com/spryker/product-bundle-carts-rest-api) (Legacy Glue)
- [ProductBundleDiscountConnector ^1.1.0](https://github.com/spryker/product-bundle-discount-connector) (Connector)
- [ProductBundleProductListConnector ^1.0.0](https://github.com/spryker/product-bundle-product-list-connector) (Connector)
- [ProductBundlesRestApi ^1.0.0](https://github.com/spryker/product-bundles-rest-api) (Legacy Glue)
