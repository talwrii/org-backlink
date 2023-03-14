# org-backlink

Show backlinks for [org-mode](https://orgmode.org/) entries.

When taking notes in org it is useful to add links to other notes with related content. However, if you add a link from A to B then obviously B is also related to A, so the user should see the connection without having too manually add a link from B to A. This is what this package does. 

# Using this package:

1. Run `M-x org-backlink-mode-refresh-cache` which scans your org files (your agenda files by default) for links.
1. Then you can turn on the `org-backlink-mode` minor mode in an org buffer which automatically shows backlinks to the current entry.

Here's a screenshot using the Org Manual as an example: 
![Screenshot](https://raw.githubusercontent.com/codecoll/org-backlink/master/screenshot.png)

If you don't want to see a message if the entry has no backlinks then set org-backlink-mode-show-no-backlink-message to nil.
