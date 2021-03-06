#### [Back To Overview](https://github.com/fastlane/itc-api-docs/)

# Resolution Center Response


### Success:

```json
{
	"data": {
		"sectionErrorKeys": [],
		"sectionInfoKeys": [],
		"sectionWarningKeys": [],
		"replyConstraints": {
			"minLength": 1,
			"maxLength": 4000
		},
		"appNotes": {
			"threads": [{
				"id": "206695",
				"versionId": "812649",
				"version": "0.9.13",
				"messages": [{
					"from": "Apple",
					"date": 1435181415000,
					"body": "<b>2.16 Details</b><BR/><BR/>Your app declares support for audio in the UIBackgroundModes key in your Info.plist, but we were unable to play any audible content when the application was running in the background.<BR/><BR/><b>Next Steps</b><BR/><BR/>The audio key is intended for use by applications that provide audible content to the user while in the background, such as music player or streaming audio applications. Please revise your app to provide audible content to the user while the app is in the background or remove the \"audio\" setting from the UIBackgroundModes key.<BR/><BR/><b>Resources</b><BR/><BR/>If you have difficulty reproducing a reported issue, please try testing the workflow described in <a href=\"https://developer.apple.com/library/ios/qa/qa1764/\">Technical Q&A QA1764: How to reproduce bugs reported against App Store submissions</a>.<BR/><BR/>If you have code-level questions after utilizing the above resources, you may wish to consult with <a href=\"https://developer.apple.com/support/technical/submit/\">Apple Developer Technical Support</a>. When the DTS engineer follows up with you, please be ready to provide:<BR/>- complete details of your rejection issue(s)<BR/>- screenshots<BR/>- steps to reproduce the issue(s)<BR/>- <a href=\"https://developer.apple.com/library/ios/#technotes/tn2008/tn2151.html\">symbolicated crash logs</a> - if your issue results in a crash log<BR/><BR/>",
					"appleMsg": true,
					"tokens": [],
					"hasObjectionableContent": false,
					"qcRejectionReasons": [{
						"section": "2.16",
						"description": " Multitasking Apps may only use background services for their intended purposes: VoIP, audio playback, location, task completion, local notifications, etc."
					}]
				}],
				"active": true,
				"canDeveloperAddNote": true,
				"metadataRejected": false,
				"binaryRejected": true
			}]
		},
		"betaNotes": {
			"threads": []
		},
		"appMessages": {
			"threads": []
		}
	},
	"messages": {
		"warn": null,
		"error": null,
		"info": null
	},
	"statusCode": "SUCCESS"
}
```

#### [Back To Overview](https://github.com/fastlane/itc-api-docs/)
