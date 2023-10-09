---
title: "Visitor's log"
layout: ../../layouts/post.astro
pubDate: 2021-02-01
description: "Web app for managing visits in a company."
image:
  url: "https://media.licdn.com/dms/image/C4E05AQGFCiVn9NiDIw/videocover-high/0/1637689114366?e=1697493600&v=beta&t=gOwaUdtbVEzFo_3Egqd89MmG5yrY1jCVcQS2TWInlyI"
  thumb: "https://media.licdn.com/dms/image/C4E05AQGFCiVn9NiDIw/videocover-high/0/1637689114366?e=1697493600&v=beta&t=gOwaUdtbVEzFo_3Egqd89MmG5yrY1jCVcQS2TWInlyI"
  alt: "Petr Krejcik giving a talk about Service Workers"
tags:
  [
    "Javascript",
    "React",
    "Node",
    "MUI",
    "Firebase",
    "Jest",
    "Cypress"
  ]
---
<h2 class="text-xl font-bold">My role</h2>

My responsibility was to lead the project from both technical and product perspective. The project was created in a team of two - myself as a senior engineer and one junior engineer. My job included a regular meetings with the client about the project definition, estimating the development process, leading the implementation, deployment and maintenance.

<br />

<h2 class="text-xl font-bold">About the app</h2>
The app is using Firebase infrastructure (authentication, Firestore, storage, hosting, functions). Every new visit is in directly (via real time queries) visible in the administration and it triggers a Firebase function which sends email and calls an API of a third party service which performs a phone call to the visited person.

Users which don't want to touch the screen can either use voice recognition to fill the fields or can scan the QR code and complete the process on their phone.

<br />

A primary use of this app is meant to be on a tablet in a kiosk mode (a user cannot leave the app).

<video src="https://dms.licdn.com/playlist/vid/C4E05AQGFCiVn9NiDIw/mp4-640p-30fp-crf28/0/1637689136238?e=1697493600&v=beta&t=ir_jVIQEKH9FlrffMxTfxy6GCxoun9-WBV2ksAvrZYA" />