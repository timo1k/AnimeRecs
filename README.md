# buildspace

### Welcome 👋

This project is a weekend build built with the starter template from [build your own AI writing assistant w/ GPT-3](https://buildspace.so/builds/ai-writer) project.

Update (2/5/23) i figured out the problem, the issue was that vercel has a 10 second timeout limit. So its either I speed up the OpenAI API request by lowering the max_tokens to 100 (max characters) or I deploy somewhere else. 
