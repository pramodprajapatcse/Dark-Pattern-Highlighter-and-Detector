This programme, created by the dapde-project's informatics team, aims to assist users in navigating the internet similarly to how they would with an ad blocker. The highlighter, however, is different from ad blockers in one very important way: instead of blocking specific dark patterns on webpages, it highlights them to make users aware of the factors that are influencing them. The tool also provides information on the kind of pattern.
How it works : The Pattern Highlighter doesn't connect to any servers; it operates fully locally within the browser. The plugin inserts a little script when a user visits a website, copying the full HTML document object (HTML DOM) inside and temporarily. A little delay of roughly 1.5 seconds occurs before the creation of a second duplicate. Then, every element of these copies is analysed both singly and in conjunction with child components by employing the applied pattern recognition techniques. Whether an element is a particular dark pattern or not is determined by the pattern detecting techniques. Two copies with a time difference are made in order to track page changes. This enables the detection of specific patterns, like countdowns. The aforementioned detection functions bear primary responsibility for the pattern detection outcomes. These are centrally defined in the patternConfig object, and constants.js contains information on the corresponding patterns. The patternConfig object is extensible indefinitely by other patterns and functions in accordance with the specifications specified in constants.js.
Features : Dark pattern identification on websites automatically
highlighting questionable content that has no effect on the way the page looks
Information on detected dark patterns is displayed in a popup window along with a description and classification.

No content blocking of the webpage Extension symbol showing the quantity of dark patterns found
The ability to highlight each identified dark pattern separately
allowing for multilingual support 

