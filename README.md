
# HSON Schema

[JSON Schema](https://json-schema.org/) for the Hedgehog Set Object Notation (HSON) format.

Helpful for validation and editor integration purposes.

## Setup for Visual Studio Code

Add the following to the end of your [settings.json](https://code.visualstudio.com/docs/getstarted/settings#_settingsjson):

```json
"files.associations": {
    "*.hson": "json"
},
"json.schemas": [
    {
        "fileMatch": [ "*.hson" ],
        "url": "https://raw.githubusercontent.com/hedge-dev/hson-schema/main/hson.schema.json"
    }
]
```
