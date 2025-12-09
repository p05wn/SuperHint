# SuperHint
IDA plugin that allows users to add comments to variable hints

# Installation
Copy `SuperHint.py` to IDA Pro plugins folder

>**Tested version** : IDA pro 8.4

# Usage
Press `Shift`+`A` to enable the feature
![gif](superhint.gif)
Click a variable or struct field in the pseudo-code and press `Shift`+`A` to add a hint comment.

![png](superhint_json.png)
When you close the database, all hint comments added to struct fields are automatically saved to JSON files.

# Features
- Supports Local variable and structure fields


# Future updates
- Supporting global variables and functions