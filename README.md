# JIRA Chrome extension
A chrome extension that queries a public JIRA API (https://jira.secondlife.com).  This is a fully functional chrome extension with a bug, some display issues, and generally some bad practices.  

**Your task is to make it production ready, make it easy for someone else to consume, and generally improve upon the code how you see fit.**

## Files:
* main.js - the :meat_on_bone: of the code that performs querys and displays results
* main.html - The UI for the request results
* manifest.json - contains metadata for the project and defines access permissions
* options.js - contains logic for saving/retrieving user values
* options.html - display for the user values
* json_results/results.json - a sample of the json values returned from a JIRA ticket(s) query

## Instructions
1. Clone the repository (or pull the code down how you wish).  Do not FORK! 
2. Refactor the code in main.js however you think it should be done. **This should be anything and everything you can think of, from refactoring to formatting.**  
   1. There's a bug that keeps the code from working, you'll need to fix that before you can get results. (once the bug is fixed, the *JIRA Activity Query* should default to a specific user and return results) 
   2. There's code missing to display the *Ticket Status Query* results, please read the response object and return the results so they can be displayed however you'd like.
3. Send us your changes however you'd like, however please do not create a PR here.  Here are a few options:
   1. Create a [Gist](https://gist.github.com/) and send us the link (preferred)
   2. Send us a .patch file [Creating a patch](https://stackoverflow.com/questions/5159185/create-a-git-patch-from-the-changes-in-the-current-working-directory)
   3. Use an online code service like [kobra.io](https://kobra.io/#/)
   4. Send us the updated file via email
  
Contact info for sending questions and final results:  denver.interview@gmail.com

## Tips
* [Installing a local chrome extension](https://developer.chrome.com/extensions/getstarted#unpacked)
* The first field in the extension should default to the word "Sunshine", if it does not, it means there is a bug that needs to be fixed first.