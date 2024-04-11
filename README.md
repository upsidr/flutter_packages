# Upsider Forked Rules of Operation for this Package

## How to cut a branch
The target branches for use with pubspeck are as follows.

| Title  | Branch Name  | Example  | Description  |
| :------------ | :------------ | :------------ | :------------ |
|  Package Branch | packages/[package_name] | packages/local_auth | Branches referenced in pubspec.yaml |
| Additional Function Branche | feature/[package_name_and_feature_name] | feture/local_auth_fix_strong_auth | Issue a PR for PACKAGES in the Additional Features branch  |

## How to update each branch
Use GitHub's "Sync fork" function to update main, and then update each packages branch based on the updated main.

# Flutter Packages

[![Release Status](https://github.com/flutter/packages/actions/workflows/release.yml/badge.svg)](https://github.com/flutter/packages/actions/workflows/release.yml)
[![Flutter CI Status](https://flutter-dashboard.appspot.com/api/public/build-status-badge?repo=packages)](https://flutter-dashboard.appspot.com/#/build?repo=packages)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/flutter/packages/badge)](https://deps.dev/project/github/flutter%2Fpackages)

This repo is a companion repo to the main [flutter repo](
https://github.com/flutter/flutter). It contains the source code for Flutter's
first-party packages (i.e., packages developed by the core Flutter team).
Check the [`packages`](./packages) directory to see all packages.

These packages are also available on [pub](https://pub.dev/flutter/packages).

## Issues

Please file any issues, bugs, or feature requests in the [main flutter
repo](https://github.com/flutter/flutter/issues/new/choose).
Issues pertaining to this repository are [labeled
"package"](https://github.com/flutter/flutter/issues?q=is%3Aopen+is%3Aissue+label%3Apackage).

## Contributing

If you wish to contribute a new package to the Flutter ecosystem, please
see the documentation for [developing packages](https://flutter.io/developing-packages/). You can store
your package source code in any GitHub repository (the present repo is only
intended for packages developed by the core Flutter team). Once your package
is ready you can [publish](https://flutter.io/developing-packages/#publish)
to the [pub repository](https://pub.dev/).

If you wish to contribute a change to any of the existing packages in this repo,
please review our [contribution guide](https://github.com/flutter/packages/blob/main/CONTRIBUTING.md),
and send a [pull request](https://github.com/flutter/packages/pulls).

## Packages

These are the packages hosted in this repository:

| Package | Pub | Points | Popularity | Issues | Pull requests |
|---------|-----|--------|------------|--------|---------------|
| [animations](./packages/animations/) | [![pub package](https://img.shields.io/pub/v/animations.svg)](https://pub.dev/packages/animations) | [![pub points](https://img.shields.io/pub/points/animations)](https://pub.dev/packages/animations/score) | [![popularity](https://img.shields.io/pub/popularity/animations)](https://pub.dev/packages/animations/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20animations?label=)](https://github.com/flutter/flutter/labels/p%3A%20animations) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20animations?label=)](https://github.com/flutter/packages/labels/p%3A%20animations) |
| [camera](./packages/camera/) | [![pub package](https://img.shields.io/pub/v/camera.svg)](https://pub.dev/packages/camera) | [![pub points](https://img.shields.io/pub/points/camera)](https://pub.dev/packages/camera/score) | [![popularity](https://img.shields.io/pub/popularity/camera)](https://pub.dev/packages/camera/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20camera?label=)](https://github.com/flutter/flutter/labels/p%3A%20camera) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20camera?label=)](https://github.com/flutter/packages/labels/p%3A%20camera) |
| [cross\_file](./packages/cross_file/) | [![pub package](https://img.shields.io/pub/v/cross_file.svg)](https://pub.dev/packages/cross_file) | [![pub points](https://img.shields.io/pub/points/cross_file)](https://pub.dev/packages/cross_file/score) | [![popularity](https://img.shields.io/pub/popularity/cross_file)](https://pub.dev/packages/cross_file/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20cross_file?label=)](https://github.com/flutter/flutter/labels/p%3A%20cross_file) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20cross_file?label=)](https://github.com/flutter/packages/labels/p%3A%20cross_file) |
| [css\_colors](./packages/css_colors/) | [![pub package](https://img.shields.io/pub/v/css_colors.svg)](https://pub.dev/packages/css_colors) | [![pub points](https://img.shields.io/pub/points/css_colors)](https://pub.dev/packages/css_colors/score) | [![popularity](https://img.shields.io/pub/popularity/css_colors)](https://pub.dev/packages/css_colors/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20css_colors?label=)](https://github.com/flutter/flutter/labels/p%3A%20css_colors) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20css_colors?label=)](https://github.com/flutter/packages/labels/p%3A%20css_colors) |
| [cupertino\_icons](./third_party/packages/cupertino_icons/) | [![pub package](https://img.shields.io/pub/v/cupertino_icons.svg)](https://pub.dev/packages/cupertino_icons) | [![pub points](https://img.shields.io/pub/points/cupertino_icons)](https://pub.dev/packages/cupertino_icons/score) | [![popularity](https://img.shields.io/pub/popularity/cupertino_icons)](https://pub.dev/packages/cupertino_icons/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20cupertino_icons?label=)](https://github.com/flutter/flutter/labels/p%3A%20cupertino_icons) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20cupertino_icons?label=)](https://github.com/flutter/packages/labels/p%3A%20cupertino_icons) |
| [espresso](./packages/espresso/) | [![pub package](https://img.shields.io/pub/v/espresso.svg)](https://pub.dev/packages/espresso) | [![pub points](https://img.shields.io/pub/points/espresso)](https://pub.dev/packages/espresso/score) | [![popularity](https://img.shields.io/pub/popularity/espresso)](https://pub.dev/packages/espresso/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20espresso?label=)](https://github.com/flutter/flutter/labels/p%3A%20espresso) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20espresso?label=)](https://github.com/flutter/packages/labels/p%3A%20espresso) |
| [extension\_google\_sign\_in\_as\_googleapis\_auth](./packages/extension_google_sign_in_as_googleapis_auth/) | [![pub package](https://img.shields.io/pub/v/extension_google_sign_in_as_googleapis_auth.svg)](https://pub.dev/packages/extension_google_sign_in_as_googleapis_auth) | [![pub points](https://img.shields.io/pub/points/extension_google_sign_in_as_googleapis_auth)](https://pub.dev/packages/extension_google_sign_in_as_googleapis_auth/score) | [![popularity](https://img.shields.io/pub/popularity/extension_google_sign_in_as_googleapis_auth)](https://pub.dev/packages/extension_google_sign_in_as_googleapis_auth/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20extension_google_sign_in_as_googleapis_auth?label=)](https://github.com/flutter/flutter/labels/p%3A%20extension_google_sign_in_as_googleapis_auth) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20extension_google_sign_in_as_googleapis_auth?label=)](https://github.com/flutter/packages/labels/p%3A%20extension_google_sign_in_as_googleapis_auth) |
| [file\_selector](./packages/file_selector/) | [![pub package](https://img.shields.io/pub/v/file_selector.svg)](https://pub.dev/packages/file_selector) | [![pub points](https://img.shields.io/pub/points/file_selector)](https://pub.dev/packages/file_selector/score) | [![popularity](https://img.shields.io/pub/popularity/file_selector)](https://pub.dev/packages/file_selector/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20file_selector?label=)](https://github.com/flutter/flutter/labels/p%3A%20file_selector) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20file_selector?label=)](https://github.com/flutter/packages/labels/p%3A%20file_selector) |
| [flutter\_adaptive\_scaffold](./packages/flutter_adaptive_scaffold/) | [![pub package](https://img.shields.io/pub/v/flutter_adaptive_scaffold.svg)](https://pub.dev/packages/flutter_adaptive_scaffold) | [![pub points](https://img.shields.io/pub/points/flutter_adaptive_scaffold)](https://pub.dev/packages/flutter_adaptive_scaffold/score) | [![popularity](https://img.shields.io/pub/popularity/flutter_adaptive_scaffold)](https://pub.dev/packages/flutter_adaptive_scaffold/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20flutter_adaptive_scaffold?label=)](https://github.com/flutter/flutter/labels/p%3A%20flutter_adaptive_scaffold) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20flutter_adaptive_scaffold?label=)](https://github.com/flutter/packages/labels/p%3A%20flutter_adaptive_scaffold) |
| [flutter\_image](./packages/flutter_image/) | [![pub package](https://img.shields.io/pub/v/flutter_image.svg)](https://pub.dev/packages/flutter_image) | [![pub points](https://img.shields.io/pub/points/flutter_image)](https://pub.dev/packages/flutter_image/score) | [![popularity](https://img.shields.io/pub/popularity/flutter_image)](https://pub.dev/packages/flutter_image/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20flutter_image?label=)](https://github.com/flutter/flutter/labels/p%3A%20flutter_image) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20flutter_image?label=)](https://github.com/flutter/packages/labels/p%3A%20flutter_image) |
| [flutter\_lints](./packages/flutter_lints/) | [![pub package](https://img.shields.io/pub/v/flutter_lints.svg)](https://pub.dev/packages/flutter_lints) | [![pub points](https://img.shields.io/pub/points/flutter_lints)](https://pub.dev/packages/flutter_lints/score) | [![popularity](https://img.shields.io/pub/popularity/flutter_lints)](https://pub.dev/packages/flutter_lints/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20flutter_lints?label=)](https://github.com/flutter/flutter/labels/p%3A%20flutter_lints) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20flutter_lints?label=)](https://github.com/flutter/packages/labels/p%3A%20flutter_lints) |
| [flutter\_markdown](./packages/flutter_markdown/) | [![pub package](https://img.shields.io/pub/v/flutter_markdown.svg)](https://pub.dev/packages/flutter_markdown) | [![pub points](https://img.shields.io/pub/points/flutter_markdown)](https://pub.dev/packages/flutter_markdown/score) | [![popularity](https://img.shields.io/pub/popularity/flutter_markdown)](https://pub.dev/packages/flutter_markdown/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20flutter_markdown?label=)](https://github.com/flutter/flutter/labels/p%3A%20flutter_markdown) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20flutter_markdown?label=)](https://github.com/flutter/packages/labels/p%3A%20flutter_markdown) |
| [flutter\_plugin\_android\_lifecycle](./packages/flutter_plugin_android_lifecycle/) | [![pub package](https://img.shields.io/pub/v/flutter_plugin_android_lifecycle.svg)](https://pub.dev/packages/flutter_plugin_android_lifecycle) | [![pub points](https://img.shields.io/pub/points/flutter_plugin_android_lifecycle)](https://pub.dev/packages/flutter_plugin_android_lifecycle/score) | [![popularity](https://img.shields.io/pub/popularity/flutter_plugin_android_lifecycle)](https://pub.dev/packages/flutter_plugin_android_lifecycle/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20flutter_plugin_android_lifecycle?label=)](https://github.com/flutter/flutter/labels/p%3A%20flutter_plugin_android_lifecycle) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20flutter_plugin_android_lifecycle?label=)](https://github.com/flutter/packages/labels/p%3A%20flutter_plugin_android_lifecycle) |
| [flutter\_template\_images](./packages/flutter_template_images/) | [![pub package](https://img.shields.io/pub/v/flutter_template_images.svg)](https://pub.dev/packages/flutter_template_images) | [![pub points](https://img.shields.io/pub/points/flutter_template_images)](https://pub.dev/packages/flutter_template_images/score) | [![popularity](https://img.shields.io/pub/popularity/flutter_template_images)](https://pub.dev/packages/flutter_template_images/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20flutter_template_images?label=)](https://github.com/flutter/flutter/labels/p%3A%20flutter_template_images) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20flutter_template_images?label=)](https://github.com/flutter/packages/labels/p%3A%20flutter_template_images) |
| [go\_router](./packages/go_router/) | [![pub package](https://img.shields.io/pub/v/go_router.svg)](https://pub.dev/packages/go_router) | [![pub points](https://img.shields.io/pub/points/go_router)](https://pub.dev/packages/go_router/score) | [![popularity](https://img.shields.io/pub/popularity/go_router)](https://pub.dev/packages/go_router/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20go_router?label=)](https://github.com/flutter/flutter/labels/p%3A%20go_router) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20go_router?label=)](https://github.com/flutter/packages/labels/p%3A%20go_router) |
| [go\_router\_builder](./packages/go_router_builder/) | [![pub package](https://img.shields.io/pub/v/go_router_builder.svg)](https://pub.dev/packages/go_router_builder) | [![pub points](https://img.shields.io/pub/points/go_router_builder)](https://pub.dev/packages/go_router_builder/score) | [![popularity](https://img.shields.io/pub/popularity/go_router_builder)](https://pub.dev/packages/go_router_builder/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20go_router_builder?label=)](https://github.com/flutter/flutter/labels/p%3A%20go_router_builder) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20go_router_builder?label=)](https://github.com/flutter/packages/labels/p%3A%20go_router_builder) |
| [google\_maps\_flutter](./packages/google_maps_flutter/) | [![pub package](https://img.shields.io/pub/v/google_maps_flutter.svg)](https://pub.dev/packages/google_maps_flutter) | [![pub points](https://img.shields.io/pub/points/google_maps_flutter)](https://pub.dev/packages/google_maps_flutter/score) | [![popularity](https://img.shields.io/pub/popularity/google_maps_flutter)](https://pub.dev/packages/google_maps_flutter/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20maps?label=)](https://github.com/flutter/flutter/labels/p%3A%20maps) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20google_maps_flutter?label=)](https://github.com/flutter/packages/labels/p%3A%20google_maps_flutter) |
| [google\_sign\_in](./packages/google_sign_in/) | [![pub package](https://img.shields.io/pub/v/google_sign_in.svg)](https://pub.dev/packages/google_sign_in) | [![pub points](https://img.shields.io/pub/points/google_sign_in)](https://pub.dev/packages/google_sign_in/score) | [![popularity](https://img.shields.io/pub/popularity/google_sign_in)](https://pub.dev/packages/google_sign_in/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20google_sign_in?label=)](https://github.com/flutter/flutter/labels/p%3A%20google_sign_in) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20google_sign_in?label=)](https://github.com/flutter/packages/labels/p%3A%20google_sign_in) |
| [image\_picker](./packages/image_picker/) | [![pub package](https://img.shields.io/pub/v/image_picker.svg)](https://pub.dev/packages/image_picker) | [![pub points](https://img.shields.io/pub/points/image_picker)](https://pub.dev/packages/image_picker/score) | [![popularity](https://img.shields.io/pub/popularity/image_picker)](https://pub.dev/packages/image_picker/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20image_picker?label=)](https://github.com/flutter/flutter/labels/p%3A%20image_picker) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20image_picker?label=)](https://github.com/flutter/packages/labels/p%3A%20image_picker) |
| [interactive\_media\_ads](./packages/interactive_media_ads/) | [![pub package](https://img.shields.io/pub/v/interactive_media_ads.svg)](https://pub.dev/packages/interactive_media_ads) | [![pub points](https://img.shields.io/pub/points/interactive_media_ads)](https://pub.dev/packages/interactive_media_ads/score) | [![popularity](https://img.shields.io/pub/popularity/interactive_media_ads)](https://pub.dev/packages/interactive_media_ads/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20interactive_media_ads?label=)](https://github.com/flutter/flutter/labels/p%3A%20interactive_media_ads) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20interactive_media_ads?label=)](https://github.com/flutter/packages/labels/p%3A%20interactive_media_ads) |
| [in\_app\_purchase](./packages/in_app_purchase/) | [![pub package](https://img.shields.io/pub/v/in_app_purchase.svg)](https://pub.dev/packages/in_app_purchase) | [![pub points](https://img.shields.io/pub/points/in_app_purchase)](https://pub.dev/packages/in_app_purchase/score) | [![popularity](https://img.shields.io/pub/popularity/in_app_purchase)](https://pub.dev/packages/in_app_purchase/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20in_app_purchase?label=)](https://github.com/flutter/flutter/labels/p%3A%20in_app_purchase) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20in_app_purchase?label=)](https://github.com/flutter/packages/labels/p%3A%20in_app_purchase) |
| [ios\_platform\_images](./packages/ios_platform_images/) | [![pub package](https://img.shields.io/pub/v/ios_platform_images.svg)](https://pub.dev/packages/ios_platform_images) | [![pub points](https://img.shields.io/pub/points/ios_platform_images)](https://pub.dev/packages/ios_platform_images/score) | [![popularity](https://img.shields.io/pub/popularity/ios_platform_images)](https://pub.dev/packages/ios_platform_images/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20ios_platform_images?label=)](https://github.com/flutter/flutter/labels/p%3A%20ios_platform_images) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20ios_platform_images?label=)](https://github.com/flutter/packages/labels/p%3A%20ios_platform_images) |
| [local\_auth](./packages/local_auth/) | [![pub package](https://img.shields.io/pub/v/local_auth.svg)](https://pub.dev/packages/local_auth) | [![pub points](https://img.shields.io/pub/points/local_auth)](https://pub.dev/packages/local_auth/score) | [![popularity](https://img.shields.io/pub/popularity/local_auth)](https://pub.dev/packages/local_auth/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20local_auth?label=)](https://github.com/flutter/flutter/labels/p%3A%20local_auth) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20local_auth?label=)](https://github.com/flutter/packages/labels/p%3A%20local_auth) |
| [metrics\_center](./packages/metrics_center/) | [![pub package](https://img.shields.io/pub/v/metrics_center.svg)](https://pub.dev/packages/metrics_center) | [![pub points](https://img.shields.io/pub/points/metrics_center)](https://pub.dev/packages/metrics_center/score) | [![popularity](https://img.shields.io/pub/popularity/metrics_center)](https://pub.dev/packages/metrics_center/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20metrics_center?label=)](https://github.com/flutter/flutter/labels/p%3A%20metrics_center) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20metrics_center?label=)](https://github.com/flutter/packages/labels/p%3A%20metrics_center) |
| [multicast\_dns](./packages/multicast_dns/) | [![pub package](https://img.shields.io/pub/v/multicast_dns.svg)](https://pub.dev/packages/multicast_dns) | [![pub points](https://img.shields.io/pub/points/multicast_dns)](https://pub.dev/packages/multicast_dns/score) | [![popularity](https://img.shields.io/pub/popularity/multicast_dns)](https://pub.dev/packages/multicast_dns/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20multicast_dns?label=)](https://github.com/flutter/flutter/labels/p%3A%20multicast_dns) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20multicast_dns?label=)](https://github.com/flutter/packages/labels/p%3A%20multicast_dns) |
| [palette\_generator](./packages/palette_generator/) | [![pub package](https://img.shields.io/pub/v/palette_generator.svg)](https://pub.dev/packages/palette_generator) | [![pub points](https://img.shields.io/pub/points/palette_generator)](https://pub.dev/packages/palette_generator/score) | [![popularity](https://img.shields.io/pub/popularity/palette_generator)](https://pub.dev/packages/palette_generator/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20palette_generator?label=)](https://github.com/flutter/flutter/labels/p%3A%20palette_generator) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20palette_generator?label=)](https://github.com/flutter/packages/labels/p%3A%20palette_generator) |
| [path\_provider](./packages/path_provider/) | [![pub package](https://img.shields.io/pub/v/path_provider.svg)](https://pub.dev/packages/path_provider) | [![pub points](https://img.shields.io/pub/points/path_provider)](https://pub.dev/packages/path_provider/score) | [![popularity](https://img.shields.io/pub/popularity/path_provider)](https://pub.dev/packages/path_provider/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20path_provider?label=)](https://github.com/flutter/flutter/labels/p%3A%20path_provider) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20path_provider?label=)](https://github.com/flutter/packages/labels/p%3A%20path_provider) |
| [pigeon](./packages/pigeon/) | [![pub package](https://img.shields.io/pub/v/pigeon.svg)](https://pub.dev/packages/pigeon) | [![pub points](https://img.shields.io/pub/points/pigeon)](https://pub.dev/packages/pigeon/score) | [![popularity](https://img.shields.io/pub/popularity/pigeon)](https://pub.dev/packages/pigeon/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20pigeon?label=)](https://github.com/flutter/flutter/labels/p%3A%20pigeon) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20pigeon?label=)](https://github.com/flutter/packages/labels/p%3A%20pigeon) |
| [platform](./packages/platform/) | [![pub package](https://img.shields.io/pub/v/platform.svg)](https://pub.dev/packages/platform) | [![pub points](https://img.shields.io/pub/points/platform)](https://pub.dev/packages/platform/score) | [![popularity](https://img.shields.io/pub/popularity/platform)](https://pub.dev/packages/platform/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20platform?label=)](https://github.com/flutter/flutter/labels/p%3A%20platform) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20platform?label=)](https://github.com/flutter/packages/labels/p%3A%20platform) |
| [pointer\_interceptor](./packages/pointer_interceptor/) | [![pub package](https://img.shields.io/pub/v/pointer_interceptor.svg)](https://pub.dev/packages/pointer_interceptor) | [![pub points](https://img.shields.io/pub/points/pointer_interceptor)](https://pub.dev/packages/pointer_interceptor/score) | [![popularity](https://img.shields.io/pub/popularity/pointer_interceptor)](https://pub.dev/packages/pointer_interceptor/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20pointer_interceptor?label=)](https://github.com/flutter/flutter/labels/p%3A%20pointer_interceptor) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20pointer_interceptor?label=)](https://github.com/flutter/packages/labels/p%3A%20pointer_interceptor) |
| [plugin\_platform\_interface](./packages/plugin_platform_interface/) | [![pub package](https://img.shields.io/pub/v/plugin_platform_interface.svg)](https://pub.dev/packages/plugin_platform_interface) | [![pub points](https://img.shields.io/pub/points/plugin_platform_interface)](https://pub.dev/packages/plugin_platform_interface/score) | [![popularity](https://img.shields.io/pub/popularity/plugin_platform_interface)](https://pub.dev/packages/plugin_platform_interface/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20plugin_platform_interface?label=)](https://github.com/flutter/flutter/labels/p%3A%20plugin_platform_interface) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20plugin_platform_interface?label=)](https://github.com/flutter/packages/labels/p%3A%20plugin_platform_interface) |
| [process](./packages/process/) | [![pub package](https://img.shields.io/pub/v/process.svg)](https://pub.dev/packages/process) | [![pub points](https://img.shields.io/pub/points/process)](https://pub.dev/packages/process/score) | [![popularity](https://img.shields.io/pub/popularity/process)](https://pub.dev/packages/process/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20process?label=)](https://github.com/flutter/flutter/labels/p%3A%20process) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20process?label=)](https://github.com/flutter/packages/labels/p%3A%20process) |
| [quick\_actions](./packages/quick_actions/) | [![pub package](https://img.shields.io/pub/v/quick_actions.svg)](https://pub.dev/packages/quick_actions) | [![pub points](https://img.shields.io/pub/points/quick_actions)](https://pub.dev/packages/quick_actions/score) | [![popularity](https://img.shields.io/pub/popularity/quick_actions)](https://pub.dev/packages/quick_actions/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20quick_actions?label=)](https://github.com/flutter/flutter/labels/p%3A%20quick_actions) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20quick_actions?label=)](https://github.com/flutter/packages/labels/p%3A%20quick_actions) |
| [google\_identity\_services\_web](./packages/google_identity_services_web/) | [![pub package](https://img.shields.io/pub/v/google_identity_services_web.svg)](https://pub.dev/packages/google_identity_services_web) | [![pub points](https://img.shields.io/pub/points/google_identity_services_web)](https://pub.dev/packages/google_identity_services_web/score) | [![popularity](https://img.shields.io/pub/popularity/google_identity_services_web)](https://pub.dev/packages/google_identity_services_web/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20google_identity_services_web?label=)](https://github.com/flutter/flutter/labels/p%3A%20google_identity_services_web) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20google_identity_services_web?label=)](https://github.com/flutter/packages/labels/p%3A%20google_identity_services_web) |
| [rfw](./packages/rfw/) | [![pub package](https://img.shields.io/pub/v/rfw.svg)](https://pub.dev/packages/rfw) | [![pub points](https://img.shields.io/pub/points/rfw)](https://pub.dev/packages/rfw/score) | [![popularity](https://img.shields.io/pub/popularity/rfw)](https://pub.dev/packages/rfw/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20rfw?label=)](https://github.com/flutter/flutter/labels/p%3A%20rfw) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20rfw?label=)](https://github.com/flutter/packages/labels/p%3A%20rfw) |
| [shared\_preferences](./packages/shared_preferences/) | [![pub package](https://img.shields.io/pub/v/shared_preferences.svg)](https://pub.dev/packages/shared_preferences) | [![pub points](https://img.shields.io/pub/points/shared_preferences)](https://pub.dev/packages/shared_preferences/score) | [![popularity](https://img.shields.io/pub/popularity/shared_preferences)](https://pub.dev/packages/shared_preferences/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20shared_preferences?label=)](https://github.com/flutter/flutter/labels/p%3A%20shared_preferences) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20shared_preferences?label=)](https://github.com/flutter/packages/labels/p%3A%20shared_preferences) |
| [standard\_message\_codec](./packages/standard_message_codec/) | [![pub package](https://img.shields.io/pub/v/standard_message_codec.svg)](https://pub.dev/packages/standard_message_codec) | [![pub points](https://img.shields.io/pub/points/standard_message_codec)](https://pub.dev/packages/standard_message_codec/score) | [![popularity](https://img.shields.io/pub/popularity/standard_message_codec)](https://pub.dev/packages/standard_message_codec/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20standard_message_codec?label=)](https://github.com/flutter/flutter/labels/p%3A%20standard_message_codec) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20standard_message_codec?label=)](https://github.com/flutter/packages/labels/p%3A%20standard_message_codec) |
| [two\_dimensional\_scrollables](./packages/two_dimensional_scrollables/) | [![pub package](https://img.shields.io/pub/v/two_dimensional_scrollables.svg)](https://pub.dev/packages/two_dimensional_scrollables) | [![pub points](https://img.shields.io/pub/points/two_dimensional_scrollables)](https://pub.dev/packages/two_dimensional_scrollables/score) | [![popularity](https://img.shields.io/pub/popularity/two_dimensional_scrollables)](https://pub.dev/packages/two_dimensional_scrollables/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20two_dimensional_scrollables?label=)](https://github.com/flutter/flutter/labels/p%3A%20two_dimensional_scrollables) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20two_dimensional_scrollables?label=)](https://github.com/flutter/packages/labels/p%3A%20two_dimensional_scrollables) |
| [url\_launcher](./packages/url_launcher/) | [![pub package](https://img.shields.io/pub/v/url_launcher.svg)](https://pub.dev/packages/url_launcher) | [![pub points](https://img.shields.io/pub/points/url_launcher)](https://pub.dev/packages/url_launcher/score) | [![popularity](https://img.shields.io/pub/popularity/url_launcher)](https://pub.dev/packages/url_launcher/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20url_launcher?label=)](https://github.com/flutter/flutter/labels/p%3A%20url_launcher) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20url_launcher?label=)](https://github.com/flutter/packages/labels/p%3A%20url_launcher) |
| [video\_player](./packages/video_player/) | [![pub package](https://img.shields.io/pub/v/video_player.svg)](https://pub.dev/packages/video_player) | [![pub points](https://img.shields.io/pub/points/video_player)](https://pub.dev/packages/video_player/score) | [![popularity](https://img.shields.io/pub/popularity/video_player)](https://pub.dev/packages/video_player/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20video_player?label=)](https://github.com/flutter/flutter/labels/p%3A%20video_player) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20video_player?label=)](https://github.com/flutter/packages/labels/p%3A%20video_player) |
| [web\_benchmarks](./packages/web_benchmarks/) | [![pub package](https://img.shields.io/pub/v/web_benchmarks.svg)](https://pub.dev/packages/web_benchmarks) | [![pub points](https://img.shields.io/pub/points/web_benchmarks)](https://pub.dev/packages/web_benchmarks/score) | [![popularity](https://img.shields.io/pub/popularity/web_benchmarks)](https://pub.dev/packages/web_benchmarks/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20web_benchmarks?label=)](https://github.com/flutter/flutter/labels/p%3A%20web_benchmarks) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20web_benchmarks?label=)](https://github.com/flutter/packages/labels/p%3A%20web_benchmarks) |
| [webview\_flutter](./packages/webview_flutter/) | [![pub package](https://img.shields.io/pub/v/webview_flutter.svg)](https://pub.dev/packages/webview_flutter) | [![pub points](https://img.shields.io/pub/points/webview_flutter)](https://pub.dev/packages/webview_flutter/score) | [![popularity](https://img.shields.io/pub/popularity/webview_flutter)](https://pub.dev/packages/webview_flutter/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20webview?label=)](https://github.com/flutter/flutter/labels/p%3A%20webview) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20webview_flutter?label=)](https://github.com/flutter/packages/labels/p%3A%20webview_flutter) |
| [xdg\_directories](./packages/xdg_directories/) | [![pub package](https://img.shields.io/pub/v/xdg_directories.svg)](https://pub.dev/packages/xdg_directories) | [![pub points](https://img.shields.io/pub/points/xdg_directories)](https://pub.dev/packages/xdg_directories/score) | [![popularity](https://img.shields.io/pub/popularity/xdg_directories)](https://pub.dev/packages/xdg_directories/score) | [![GitHub issues by-label](https://img.shields.io/github/issues/flutter/flutter/p%3A%20xdg_directories?label=)](https://github.com/flutter/flutter/labels/p%3A%20xdg_directories) | [![GitHub pull requests by-label](https://img.shields.io/github/issues-pr/flutter/packages/p%3A%20xdg_directories?label=)](https://github.com/flutter/packages/labels/p%3A%20xdg_directories) |
