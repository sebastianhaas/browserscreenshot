# browserscreenshot
A LaTeX package that renders screenshots in a minimal browser mockup, so that

<img src="https://cloud.githubusercontent.com/assets/6751545/20246695/cbcc57e4-a9bc-11e6-82e7-f6088eb772d1.png" width="400">

becomes

<img src="https://cloud.githubusercontent.com/assets/6751545/20246716/8689b57c-a9bd-11e6-8bac-46d23dcc6ac2.png" width="450">

## Usage
```latex
\browserscreenshot{screenshot.png}{https://example.com/}
```
The first argument is the image path, the second the url to be displayed in the mockup browser's address bar.

### Width of the screenshot
The screenshot's width can be set relative to `\textwidth`:
```latex
\browserscreenshot[0.3]{screenshot.png}{https://example.com/}
```
This will render the screenshot one-third of `\textwidth`. 
