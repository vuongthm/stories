---
title: "The First Product"
part: 1
preview: "I built my first product at nineteen. Seven users. Two deleted it after two days. I learned more than any classroom had taught me."
date: "2024-03-05"
lang: "en"
---

# The First Product

I built my first product at nineteen. It was a note-taking app — which meant it was exactly the same as fourteen thousand other note-taking apps — but I didn't know that yet, and not knowing it is probably why I finished it.

![The Fearless Years cover](/media/stories/fearless-years/cover.png)

Seven people used it. Two deleted it after two days. The other five probably forgot it existed.

## What I Learned

The product failed, but the failure was instructive. I learned that ideas are cheap, that shipping is the expensive part, and that "no one is using this" is the most clarifying feedback you can receive.

### The part I skipped

I skipped the conversations that should have happened before the build.

> The real failure would have been not to build it at all.

I also learned that I liked the feeling of having made something — even something small, even something that didn't work. That feeling has been more durable than any of my successes.

## The Metric That Mattered

I had set out to build something. I built it. That was the goal. The users were a bonus — a small bonus, as it turned out, but a bonus nonetheless.

What I failed to do was learn *before* shipping. I hadn't talked to a single potential user. I had built what I thought people needed, not what they actually wanted.

That mistake took me three more products to stop making.

#### A tiny checklist

| Question | Answer |
|----------|--------|
| Did I ship it? | Yes |
| Did I validate it? | No |
| Did I learn from it? | Also yes |

def launch(product):
if not product.users:
return "Ask users first"
return "Ship and measure"