# TabDL

Chrome extension for downloading content from tabs.

## Roadmap

1. Copy list of all tabs to clipboard
  1. Remove duplicate tabs
2. Download list of tabs to a text file
  1. Downloads to /tmp/ with generated file name
  2. Allow choosing the filename and save location
3. Triggers a local application which uses the tab data as configured
  1. For example, NodeJS application which fetches the HTML from provided URLs
  and executes actions based on the content.
  2. Extension could send pre-parses data points instead of URLs


