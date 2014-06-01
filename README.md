M12.Neos.NodeType.CodeSnippet
=============================

Simple `CodeSnippet` node type for Neos. It just wraps the code snippet into `<pre><code>...</code></pre>`, nothing more.

This is very basic and only temporary solution untill CodeHighlighting node element appears in TYPO3 Neos core. See
https://review.typo3.org/#/c/22062/ and https://review.typo3.org/#/c/22065/

## Installation

Add to your composer.json:
```
{
    "repositories": [
        { "type": "git", "url": "https://github.com/million12/M12.Neos.NodeType.CodeSnippet.git" }
    ],
    "require": {
        "m12/neos-nodetype-codesnippet": "dev-master"
    },
}
```
