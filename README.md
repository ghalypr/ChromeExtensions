# ChromeExtensions
Chrome extensions cores

## Read
https://developer.chrome.com/docs/extensions/mv3/getstarted/extensions-101/
https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/

## Match patterns
Host permissions and content script matching are based on a set of URLs defined by match patterns. A match pattern is essentially a URL that begins with a permitted scheme (http, https, file, or ftp, and that can contain '*' characters. The special pattern <all_urls> matches any URL that starts with a permitted scheme. Each match pattern has 3 parts:

https://developer.chrome.com/docs/extensions/mv3/match_patterns/


## Content scripts
Content scripts are files that run in the context of web pages. By using the standard Document Object Model (DOM), they are able to read details of the web pages the browser visits, make changes to them, and pass information to their parent extension.

https://developer.chrome.com/docs/extensions/mv3/content_scripts/#functionality


## Manage events with background scripts

Extensions are event based programs used to modify or enhance the Chrome browsing experience. Events are browser triggers, such as navigating to a new page, removing a bookmark, or closing a tab. Extensions monitor these events in their background script, then react with specified instructions.

A background page is loaded when it is needed, and unloaded when it goes idle. Some examples of events include:

https://developer.chrome.com/docs/extensions/mv2/background_pages/
