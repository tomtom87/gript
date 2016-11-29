+++
title = "Searching with Elastic Search in a Meteor App"
date = "2016-11-29T13:50:46+02:00"
tags = ["web", "meteor", "elastic search"]
categories = ["Web Development", "Meteor"]
menu =
description = "Build a fast, scalable, big-data search for your meteor app"
banner = "Elasticsearch.png"
+++

## Preface

Making a good working search  in Meteor has been my desire for quiet some time,
for a past client project; I was unable to implement a fully working search due to
budget constraints and had to just use a regex and mongo solution.

So I have decided to write this guide during my quest to get Elastic search working
for Meteor apps.

### Why Elastic-search?

I want to return alot of results fast and in the past I used Sphinx.
I'm already using it in a few Rails apps and it works very nicely and easily, so
I thought it would make a good match for Meteor.

So far I have tried to implement Elastic-search from the atmosphere packages; but
it was not working so we will try going it alone in this guide.
