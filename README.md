# DocuGen
An AI Agent that creates documentation for your code

## Initial Implementation/Idea for the project

1. Provide a github URL to the repo that you need to monitor
2. for each pr merged on the project configure a webhook to trigger this ai agent
3. The Ai agent has vector database that stores information about all the code that has been committed to the project
4. Agent scans the latest commit and commit message, issues related to the commit, create a summary of business flow
5. Now load the existing documentation and make appropriate changes to the documentation and raise a pr to the same repo tagging the commit id
6. Human reviews and merges the documentaion pr request.
