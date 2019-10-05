# Flutter E-Commerce App

A Flutter e-commerce starter kit built using [ScopedModel](https://pub.dartlang.org/packages/scoped_model) for state management that allows you to view a list of paginated products and its details. Originally built by the Flutter team at [GeekyAnts](www.geekyants.com).

You can checkout the complete starter kit on Flutter Market: [Link](https://fluttermarket.com/view/flutter-e-commerce-backend)

Medium tutorial: [Link](https://blog.geekyants.com/flutter-e-commerce-backend-app-2d23121fd0c8-2d23121fd0c8)

Docs for Admin dashboard: [Link](http://docs.fluttermarket.com/flutter-ecommerce-backend/)

## Setup

You need to add a `remote_config.dart` file in the `lib`>`util` directory as follows:

```
class RemoteConfig {
  static final Map<dynamic, String> config = {
    "AuthorizationToken":
        "YOUR_API_KEY",
    "BASE_URL": "www.BASE_URL.com",
    "BASE_PRODUCTS_URL": "/BASE_PRODUCTS_URL/products/categoryId=1",
  };
}
```
# wc_products
