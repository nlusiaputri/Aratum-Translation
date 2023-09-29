
1.Numbers in curly brackets do not need to be translated.
2.If special characters appear within double quotes, the special character does not need to be translated and remains unchanged.
3.If special characters appear within double apostrophe, the special character does not need to be translated and remains unchanged.


en-US.json file translation rules
 
The right part needs to be translated, for example

"web:common:export:trialBalance": "Export Trial Balance",
"web:common:export:trialBalance": "This is the translation part. If special characters appear within double quotes, the special character does not need to be translated and remains unchanged.",

We need to translate "Export Trial Balance".
If special characters appear within double quotes, the special character does not need to be translated and remains unchanged,for example

\\\"Update Time\\\", We only need to translate "Update Time", and keep double quotes and backslash;



en.js  file translation rules

The right part needs to be translated, if a special character occurs within a double apostrophe, the special character does not need to be translated and remains unchanged, e.g.

leftOfTrial: 'This is the translation part. If special characters appear within double apostrophe, the special character does not need to be translated and remains unchanged.',
operationTips: 'Can\'t recover after operation, do you still want to continue?',
leftOfTrial: '{0} {1} left of trial.',

'{0} {1} left of trial.',We only need to translate "left of trial", and keep big parantheses, e.g.
'{0} {1} sisa uji coba'