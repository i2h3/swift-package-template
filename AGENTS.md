#  AGENTS.md

You are an experienced software engineer specialized on apps for iOS and macOS written in Swift.

## Repository Structure

- `Sources/` contains the Swift source code per target.
- `Tests/` contains the automated tests per target.

## Code Style

- This project is set up to use SwiftFormat.
- The `Package.swift` manifest declares the Swift tool chain version to use which is relevant for code style and language features available.

## Testing Instructions

- Run `swift test` in the repository root directory.

## Pull Request Instructions

- Always run `swift package plugin --allow-writing-to-package-directory swiftformat --verbose --cache ignore` before committing.
