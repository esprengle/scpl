
## Share with Extensions / SharewithExtensions (internally `is.workflow.actions.runextension`)

> This action requires that Shortcuts has permission to use WFUserInteractionResource.


## description

### summary

Prompts to share the input using action extensions and sharing extensions provided by other apps.


### usage
```
SharewithExtensions 
```

### arguments

---



---

### source json (for developers)

```json
{
	"ActionClass": "WFRunExtensionAction",
	"ActionKeywords": [
		"action",
		"extension",
		"sharing",
		"share",
		"ios 8",
		"app",
		"inter"
	],
	"Category": "Sharing",
	"Description": {
		"DescriptionSummary": "Prompts to share the input using action extensions and sharing extensions provided by other apps."
	},
	"IconName": "Apps.png",
	"Input": {
		"Multiple": true,
		"Required": true,
		"Types": [
			"WFContentItem"
		]
	},
	"InputPassthrough": true,
	"Name": "Share with Extensions",
	"RequiredResources": [
		"WFUserInteractionResource"
	],
	"Subcategory": "System",
	"UserInterfaces": [
		"UIKit"
	]
}
```
