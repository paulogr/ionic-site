---
layout: post
title:  "Invite a friend to your Ionic App"
date:   "2015-03-17  8:00:00"
categories: ionic, ionicio
author: '<img src="http://www.gravatar.com/avatar/e130a4be9fba5eb5d932c813fbe3a58d?s=48&amp;d=mm" class="author-icon"><a href="http://twitter.com/maxlynch" target="_blank">@maxlynch</a>'
published: true
---

One of the biggest requests for [Ionic View](http://view.ionic.io/) and [ionic.io](http://ionic.io/) is to be able to invite co-workers, friends, and customers to preview and test your app. This would make the Ionic View app a great beta-testing experience that is quite a bit easier to use than TestFlight, etc.

Now you can! To invite someone to view and test your app, just run:

```bash
$ ionic share EMAIL
```

to share the current app with the person at that email address.

To use this new feature, make sure to update to the newest version of Ionic CLI and upload your app to ionic.io:

```bash
$ ionic login
$ ionic upload
$ ionic share EMAIL
```

Also, soon you'll be able to share right from Ionic View and ionic.io. Enjoy!
