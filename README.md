Adobe CQ Ticket 115263
========


# Overview
This is the repository that belongs to Adobe CQ Ticket 115263. It was developed in the quickstart version of AEM
with the geometrixx websites installed.

It contains:

* sample tag collections in /etc/tags
  * articles
  * Review
  * testing
* a component called testcomponent in apps/myproject/components/testcomponent.  This component has a dialog containing one tab (Review Process). This tab
contains amongs others a widget for selecting a tag from the tag collection 'review'. Bot the classic dialog (dialog.xml) as the touch UI version (cq:dialog) are available.
* a testpage called test under /content/geometrixx-outdoors/en that contains this testcomponent

# Recap of the issues

* *autocomplete search not limited to rootpath in Touch UI*: The autocomplete textfield is not limited to the Review tags. It shows tags from other collections as well;
* *tagcloud not limited to rootpath in Touch UI*:  The tagcloud below the textfield is not limited to the Review tags. It shows tags from other collections as well;
* *removal of tags does not work in Touch UI*






