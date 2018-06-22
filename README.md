# react-native-photolibrary-ios-enable

Adds security message to allow use of the photo library without requiring XCode intervention

# Usage

```bash
yarn add react-native-photolibrary-ios-enable
```

**Note** You can determine the text for the camera permission message via the `IOSPhotoLibraryPrivacyText` and `IOSPhotoLibraryAddPrivacyText` properties of your `package.json` file. To set text, just set the value like so before adding the package:

```
{
    ...
    dependencies: {
        ...
    },
    IOSPhotoLibraryPrivacyText: "Please let me use the camera!",
    IOSPhotoLibraryAddPrivacyText: "Please let me save pictures to your camera roll!"
}
```
