---
layout: post
title:  "A guide to migrating from a WordPress site to another WordPress site."
author: "Mark Spurgeon"
description: "We have failed doing that, so you don't have to !"
---

About a year ago, our website’s WordPress was so old that it stopped 
working altogether. Suddenly, all of our articles were hidden from everyone. 
In somewhat of a panic, we had to re-create a new WordPress site and figure 
out a way to migrate all of our data. That task may sound straightforward, 
but it was far from it. 

This guide will hopefully help you, and my future self, to avoid mistakes doing so.

The challenge
----

Depending on what goes into your website, the migration process may vary. 
If you still have access to your admin page, and have very little data to 
transfer, you should consider using a **plugin**.

In our case, we had to make sure these elements were imported :

* Posts, with specific metadata
* Coauthors
* Media

While we tried to import images, we very quickly realised that *none of the plugins were useful*.

1 - Create your new WordPress site
----

I wont get into the installation process. But in order to import our database, we have 
to *remember the name of the database used by WordPress*.

