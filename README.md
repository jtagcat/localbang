# `localbang`
`localbang` provides DuckDuckGo, and user-defined bangs locally in Firefox. Aiming to cut down on required mind space, time spent, and waiting, while searching.

### Example, making a search on GitHub:
 - The norm defined by society:
    1. (Searching `github` on an engine, and navigating to it.) (typing time + 1 page load + mouse(/keyboard) navigation)
    1. (or) Typing in `g`(ithub.com) and pressing enter. (typing time + 1 page load)
    1. Locating and activating the search bar on the site. (few seconds of user time wasted)
    1. Entering the query. (typing time + 1 page load)
 - The [DuckDuckGo bang](https://duckduckgo.com/bang) way:
    1. Type in `!gh search query here` and press enter. (typing time + 1 page load)
    1. User gets _redirected_ to search result for term `search query here` (1 page load, no user interaction, or mind space needed)
 - `localbang`:
    1. Type in `!gh search query here` and press enter. (typing time + 1 page load)
    
    
 ### `localbang`'s advantages over DDG:
  - Configurable bangs(, that are compatible with dotfile sharing!)
  - Configurable (or no) bang prefix. (default is `!`)
  - Speed. 1 less page load.
  - Trust no other party with your (search) data.
  
  #### Disadvantages:
   - Updates are not automatic.

## Browser compatability
`localbang` is supported, and so far known to only work with Firefox (and forks), using the [key](https://support.mozilla.org/en-US/kb/bookmarks-firefox#w_how-to-use-keywords-with-bookmarks)[words](https://support.mozilla.org/en-US/kb/how-search-from-address-bar) feature in bookmarks.

## Credits
[DuckDuckGo](https://duckduckgo.com), a privacy-oriented search engine, for maintaining their large global bang list.
