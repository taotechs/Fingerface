# Fingerface

Redirect all API requests from `FingerprintManager` to `BiometricManager` and `BiometricPrompt`.
This allows users to use Face Unlock in apps that only support fingerprints; very useful for devices such as Pixel 4 and Pixel 4 XL as they no longer have fingerprint scanners, and most apps out there are not updated to use `BiometricPrompt` yet.

## Requirements

- Android 10.0 or above
- Xposed Framework (Magisk + Edxposed)

## Downloads

[Latest Release](https://github.com/topjohnwu/Fingerface/releases/latest)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
