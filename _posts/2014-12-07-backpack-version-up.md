---
layout: post
title: backpack version up
tags: backpack notice
category: eng
---


<img src="/images/pizzaimg/excuses.jpg" alt="make pizza, not excuses"
title="make pizza, not excuses" style="height: 460px; margin-left: auto;
margin-right: auto; display: block;">

We all feel like it's been longer, but it's only been 2.5 weeks. We
procrastinated a little bit (and have real jobs, kinda), but a
[milestone](https://github.com/teampizza/backpack/milestones?state=closed) is a
milestone, especially when somebody sticks a due date on it.

So. Welcome to **v0.2**, our second alpha. The
[proof-of-concept detection model](https://github.com/teampizza/backpack/tree/devel/backend/modeler/models/socialbeacon)
now conforms to our newly written
[draft model spec](https://github.com/teampizza/backpack/blob/devel/docs/modelspec.md),
and the backend is pluggable (if you
[study the code](https://github.com/teampizza/backpack/blob/devel/backend/modeler/model_master.js#L24)).
This means that anybody with the chops can sit down and whip up a model for
detecting personal information leaks, and slot it right in.

This release is still squarely aimed at developers. Sit tight, regular
users. We'll get a beta to you yet.
