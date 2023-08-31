# Prompt Engineering with OpenAI API

To install the OpenAI Python library:

```
pip install openai
```

The library needs to be configured with your account's secret key, which is available on the website.

You can either set it as the OPENAI_API_KEY environment variable before using the library:

```
export OPENAI_API_KEY='sk-...'
````

Or, set `openai.api_key` to its value:

```
import openai
openai.api_key = "sk-..."
```

Course: https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/