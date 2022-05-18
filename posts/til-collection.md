---
title: TIL Collection Version 1
date: 2022-04-03
status: draft
---

## Introduction

This is version 1 of a compiled list of "TIL's" (Today I Learned).

### Using href:tel with Next.js

When using `href:tel`, you can not attach it simply as `<Link href={"tel:0001234567"}>` component, because,
the `<Link>` components is really only meant for page routing. In this case you want to use a regular `<a>` tag.

I think its important for new Next.js devs to
understand that Next.js' included components (`<Image>`, `<Link>`, etc) are not always preferable, and at some point one should consider looking into the details of how they work.
