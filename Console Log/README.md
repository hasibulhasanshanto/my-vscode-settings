# VSCode sets the console.log shortcut

1. Open vscode, select file-->Preferences-->User code snippet
2. Select the javascript type and open the javascript.json file.
3. Follow the action, set the shortcut input

```javascript

{
	"Print to console": {
			"prefix": "cl",
			"body": [
				"console.log('$1');",
			],
			"description": "Log output to console"
		}


```