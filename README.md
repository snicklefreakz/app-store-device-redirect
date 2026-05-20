# App Store Device Redirect page
Simple single-page HTML + vanilla JavaScript app store redirect page based on userAgent.
Can be used as template for individual implementations.

## Functionality
Provides a static HTML page to redirect users to the app store of their device. Shows platforms buttons on fallback.
The detection is based on the userAgent:
`var userAgent = navigator.userAgent || navigator.vendor || window.opera;`

## Supported platforms & userAgents
- Android ("android")
- Apple ("iPad|iPhone|iPod|Macintosh")
- Windows ("Win")
- Linux ("Linux")
