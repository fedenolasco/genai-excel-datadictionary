# genai-excel-datadictionary

## Purpose
This Excel template is used to simulate the autogeneration of data dictionary descriptions. It uses the dataset physical metadata as well as some "explicit context" to steer the LLM to provide context-specific descriptions.

## Article Sources
The original article was first published on my blog:
https://datatunnel.io/2023/11/17/generative-ai-and-data-dictionary-descriptions/

Additional distributions of this article exists:
https://medium.com/@fedenolasco/generative-ai-and-data-dictionary-descriptions-a2ba8c832afb
https://www.linkedin.com/pulse/generative-ai-data-dictionary-descriptions-fede-nolasco-xrrze/

## Tooling

In order to run this Excel file you require:
### Excel labs plugin
https://appsource.microsoft.com/en-us/product/office/WA200003696

### Open API Key
https://platform.openai.com/account/api-keys

## Support
This was a one off experiment and I do not provide support, but you are free to use Excel solution for your own experiments.

## Excel Usage
The Excel file is for demo purposes
/workspaces/genai-excel-datadictionary/titanic example gen ai draft writing rate v4 reset - no api.xlsm

* It comes without an Openai API key.
* Once you get an API key you can test it out.
* The main Excel tab is called "component"
* When you run the demo, use the Excel buttons from left to right
* The [reset] button turn off all subsequent buttons and serve as a flag to activate/deactivate the call of teh function LABS.GENERATIVEAI(...). Many output cells use such function.
* The initial state of teh "component" tabe shows some sample values.


