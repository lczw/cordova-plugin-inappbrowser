# cordova-plugin-inappbrowser (fork)

This is a fork of `cordova-plugin-inappbrowser` by [Moodle HQ](https://moodle.com/). If you are looking for the documentation, you can read the original at [apache/cordova-plugin-inappbrowser](https://github.com/apache/cordova-plugin-inappbrowser).

## Modifications from the original

We created this fork because we needed to include the following modifications in [our mobile application](https://github.com/moodlehq/moodleapp):

| PR | Description |
| -- | ----------- |
| [#883](https://github.com/apache/cordova-plugin-inappbrowser/pull/883) | Allow loading local files in Android      |
| [#921](https://github.com/apache/cordova-plugin-inappbrowser/pull/921) | Allow changing location bg and text color |
| [#886](https://github.com/apache/cordova-plugin-inappbrowser/pull/886) | Allow loading of intent urls              |

You can see all the changes here: [5.0.0...moodlemobile:v5.0.0-moodle.3](https://github.com/apache/cordova-plugin-inappbrowser/compare/5.0.0...moodlemobile:v5.0.0-moodle.3)

## Installation

You can install this package using the [original installation instructions](https://github.com/apache/cordova-plugin-inappbrowser#installation), but installing this package instead:

```sh
cordova plugin add @moodlehq/cordova-plugin-inappbrowser@5.0.0-moodle.3
```
