To add a new chapter, copy the text in "template_chapter.md", and go to "content/chapters/" and "add_file/create_new_file", and name the file appropriately, such as "chapter_x.md" or "chapter_xstar.md".

Paste in the content from "template_chapter.md"

Add *stars* around any text that should be italicized, and find those pesky [^pesky_footnotes] (making sure to add them at the bottom under the ---), and then delete the link to the [next chapter], because it will fail if the next chapter doesn't exist.

Hit "Commit to master" and it will save the file.

To check if everything went OK, you can go to "Actions" and look for a Green Checkmark next to the highest Action.
If it shows a red X, something went wrong. 
To see what went wrong, you can "click" on the Action, then "deploy", and most likely "Build" will have the X.
Look for **ERROR**. For example, in [this example](https://github.com/rmflight/symbiosisnovel/runs/835999635?check_suite_focus=true#step:5:10), I tried to link to "chapter_2star.md", which doesn't exist, instead of "chapter-2star.md", which is the actual chapter.

If everything's green, then you can go to ".../symbiosysnovel" and the site should be updated.