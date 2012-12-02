
The downloadable code and screenshots for my book, "Programming iOS 5: Fundamentals of iPhone, iPad, and iPod touch Development," published by O'Reilly in March 2012, have now been moved off to the subfolder iOS5bookExamples.

At the top level, I've begun revising the examples to fit iOS 6. So far I've revised the existing examples for chapters 1 through 31.

Changes include:

* Use new literals and subscripting for arrays, dictionaries, numbers.

* Use autosynthesis of properties.

* Use constraints (instead of frame) to position and size subviews, whenever this is relational (and doesn't get in the way of the example).

* Illustrate some newly available CIFilters.

* Illustrate new UIView/UIGestureRecognizer interaction.

* Illustrate new rotation rules, including new structure of launch-into-rotation.

* For table views, use exclusively new register-and-dequeue architecture.

New examples include:

* Further illustrate use of constraints (ch 14), esp. in company with animation (ch 17).

* Show gesture recognizers in nib (ch 18).

* Show new rotation/orientation rules (ch 19).

* Show new state save-and-restore (ch 19).

* Show new storyboard features: container controller, Exit (unwind).

* Show collection views.

* Other new iOS 6 features as they arise.

This list is not exhaustive by any means. If you really want to know everything that I've changed, clone to your computer and do a diff against commit 25644891 (that's when I started this rounded of revision).

Matt Neuburg
