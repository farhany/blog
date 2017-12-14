---
title: "Getting the Hang of This"
date: 2017-12-13T23:27:22-08:00
---
Alright, so I've fixed the SSL issue with CloudFront. Which rocks BTW. 

There was still a JS file loaded that was loading the front page header image over http, which made the site lose the
secure green lock in Chrome. Though Safari didn't care. It doesn't show a green lock icon anyway, unless the cert is EV based.
