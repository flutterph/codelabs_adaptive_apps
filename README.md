# adaptive_app

An example project demonstrating adaptive layouts in Flutter.

![preview](.github/preview.jpg)


## Getting Started

1. Clone this repo

```
git clone https://github.com/flutterph/codelabs_adaptive_apps
```

2. Create a Youtube Data V3 API Key

First, create an API key as documented in the codelabs in [Step 3](https://codelabs.developers.google.com/codelabs/flutter-adaptive-app#3).

You can also create the API key [in the console](https://console.cloud.google.com/projectcreate) directly.

Last, replace the `youTubeApiKey` in `lib/main.dart`.

```
const youTubeApiKey = 'YOUR_API_KEY' // replace this
```

3. Run the project

Check available devices:

```
flutter devices
```

Run app in a specific device:

```
flutter run -d macos
```

Run app in all available devices:

```
flutter run -d all
```