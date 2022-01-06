---
challenge-number: 7
title: Use Jekyll to build a complete, styled blog post
author: Joe Taylor
date: 2022-01-05
layout: post
---

Today, we're going meta. Time is at a premium, so instead of doing a tech
challenge *and* a blog post, my blog post *is* my tech challenge, which makes
this the opportune time to right the wrongs of yesterday and create something in
[Jekyll](https://jekyllrb.com/) that actually feels complete and does the tool some small justice.

## My process

I followed many of the same steps for setup as yesterday, only this time it went
quicker because I didn't need to consult the docs quite so much. Practice makes
faster.

I placed an emphasis on simple, mobile friendly styles. Actually, I didn't
bother with a desktop design at all this time.

I intended to incorporate an offline webpack build for some JavaScript
enhancements to posts and templates, but ended up using CSS exclusively. I'd
never built a CSS-only hamburger menu before, and while I'd still prefer
JavaScript in any serious context, :focus-within and :focus give me all the
tools I need to make things work sans-scripting. I say CSS, but I mean SCSS. I
made full use of Jekyll's built-in preprocessor.

I think some subtle parallax would be a nice and modest touch, and I need to
pick a highlight color for links, but the design is coming along. I steered
clear of web fonts, because I want to keep the load time snappy.

## What a blog post needs

The stated goal was to write a "complete" blog post. So what is that? To really cover
all the bases, I feel I need to include a number of things in a blog post.

1. Good writing. This is rather subjective, and I don't feel I'm there yet, but
   I expect to improve steadily with time. That's one muscle that is surely
   being exercised when I blog.
2. Good content. Not only do I need to write well, but I need to pick a subject
   worth writing about, and actually have something to say.
3. Pretty pictures. I'm no artist. But even if I were to dabble here, my blog
   coul become much more visually interesting.
4. Interactivity where needed. I need to take full advantage of the features of
   the medium instead of just working around its challenges. A web post can be
   so much more than a digital piece of paper with writing on it.

What a blog post doesn't need is a lot of filler text and exposition. I'm guilty
of overdoing both.

## How Jekyll helped

The main boon for me was Jekyll's support for SCSS and Markdown, and the ability
to define includes and keep the codebase better organized than with a plain HTML
rough draft. Staying organized is great, and I suppose if I wanted to I could
reuse any template I create via Jekyll. I doubt I'll want to though. I like
building templates.

In terms of magic folders, I used _includes, _layouts, _posts, _data, and _sass.
None of these were used in an exotic or remarkable way. I went a very conventional
route.

## Conclusion

I feel I am not giving Jekyll the attention it deserves. I am happier with the
overall quality of this feature demonstration, but once again, I'm running into
the limit of what I can do in a day sooner than I'd like.
