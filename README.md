# CIS

An Xcode project for a macOS SwiftUI app. At present it contains only the default Xcode template: a single window that shows "Hello, world!". The purpose of the app is not documented in the repo yet.

## Build

Open `CIS.xcodeproj` in Xcode and run the `CIS` scheme. The deployment target is macOS 15.3.

A GitHub Actions workflow (`.github/workflows/objective-c-xcode.yml`) builds and analyzes the project on pushes and pull requests to `main`.

## Layout

| Path | What it is |
|---|---|
| `CIS/` | App source: `CISApp.swift`, `ContentView.swift`, assets, entitlements |
| `CISTests/`, `CISUITests/` | Template unit and UI test targets |
| `CIS.xcodeproj/` | Xcode project |

Part of [Techmore](https://techmore.github.io/pages/repos/).
