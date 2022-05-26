# rxofclock-desktop

This is the desktop offline edition of [rexcape/rxofclock](https://www.github.com/rexcape/rxofclock)

## Build

This repo is using Github Actions for release on tags. The workflow file is [here](./.github/workflows/publish.yml)

## Known issues

- (Windows) The sheet selection dropdown menu will appear in the wrong position after running the app and click the select element.

## Build Manually

You can build this app manually:

### Environment

- Rustc >= 1.60
- NodeJS >= 16.15.0
- pnpm >= 6

### Steps

- Clone this repo: `$ git clone https://github.com/rexcape/rxofclock-desktop.git`
- Install dependencies: `$ pnpm install`
- Build: `$ pnpm tauri build`
