---
layout: post
title: Developing the IHF App
tagline: "Mobilizing volunteers"
author: Ken Cavagnolo
category : lessons
tags: [android, osx]
comments: true
tweets: true
---

{% include JB/setup %}

<div class="blurb">

Navigation planning:
* sidebar menu
  * summary
      * my cases
      	* case list
      	  * profile pic
      	  * name
      	  * age
	  * last known location
	  * rating
	  * description
	  * photos
	  * action items
	    * assign
	    * fund
	    * promote
      * blog
      	* view posts
	  * edit
	  * delete
	  * associate w/ case
	  * share
	* new
	* approve
      	* funding
      	* promote
      * photos
      * case funding (totals, over/under, %completed, ...)
      * social (views, retweets, comments, ...)
      * my activity (days on, miles, active time, ...)
  * history
  * account
  * help
  * about

feature planning:
* two-step authentication login
* cannot login without location services enabled
* cache data locally for poor connections
* photo vault connected to Drive or Dropbox

dev done inside android studio (one of the awesome IDE's from IntelliJ)

</div>