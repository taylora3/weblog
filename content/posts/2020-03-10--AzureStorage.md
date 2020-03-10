---
title: Using Azure Storage as a mobile backend
date: "2020-03-10T23:46:37.121Z"
template: "post"
draft: false
slug: "/posts/azurestorageasabackend/"
category: "Azure"
tags:
  - "Azure"
  - "Development"
  - "Mobile"
description: "Using Azure Storage Blobs, Tables and Queues and Azure Functions is a great way to build low usage apps or for building proof of concepts"
---

Using Azure Storage Blobs, Tables and Queues is a great way to build low usage apps or for building proof of concepts.

![Azure Storage arhitecture](/media/image-2.jpg)

As part of a mobile backend rebuild I needed to create A HTTP endpoint that accepted a JSON object. That Json object had to then be saved and it's contents converted into a PDF which would then be pushed into a Document managment system.

