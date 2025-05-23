---
layout: post
title:  "Vibe Coding versus AI Pair Programming"
summary: "Lots of people are talking about vibe coding. It is the new hip thing. You give an AI a prompt and the AI spits out code. That sounds amazing . . if it works. Where AI really starts to shine today is as an AI pair. When you have an existing quality codebase on which a skilled software engineer is working, an AI pair is a powerful helper. When one knows how to ask for a very specific addition, then can review and accept code written by the AI, it does supercharge what that engineer can do. "
author: kendecanio
date: '2025-05-23 14:35:23 +0530'
category: software
thumbnail: /assets/img/posts/pair-with-ai.png
keywords: coding, AI, pair programing, vibe coding
permalink: /blog/vibe-coding-versus-ai-pair-programming/
usemathjax: true
---

Asking the question ‘can AI build software?’ is the wrong question as there is a simple answer, ‘Yes, absolutely’ but that answer is generally meaningless. Let’s explore this a bit and find a better question with a better answer.

There is the continuum of complexity from a simple, static, one-page website through to Shopify on the other. Another continuum is that of quality. There is a big difference between a demo, a project, and a product. A demo can be as simplistic as something that shows what a product might look like. A project is all about the Happy Path. It does what the product will do but only if you follow the correct path. Any deviation from that path fails and often fails badly. A product is about ensuring that no matter what the user does, and anything that can be done wrong will be done wrong at some point, your product will either work anyway or, if it fails, will fail gracefully.

The more robust, reliable, foolproof, the better the product. The code for a demo is disposable. The quality is of no consequence as long as the demo works. A project is often the same. The code for a product on which you can build and scale a company must be of quality.

Other considerations include fixability, scaleability, and extensibility. When something goes wrong, when you find a bug, how easy is it to fix the problem? When your active user base grows, can you scale your product to effectively support them or does your product start to fail under the growing load? When it’s time to add new features, how easy is it to add additional code to bring that new feature such that your codebase is still fixable, scaleable, and extensible?

Remember, the question of coding speed is not how fast one can write any code but how fast one can write the needed code. If it is for a demo and the code is disposable, if the code shows what you want, it’s probably the right code. If it is for a product on top of which you want to build and scale your company, quality is important.

Again, ‘can AI build software?’ is the wrong question. With what we have established, a better question is, ‘for a given complexity and quality, can AI write that code?” If you are looking for the code to run most websites, the answer is almost certainly yes. If you are building a demo and the code is disposable, probably. If you are building a web application, one where one must log in and each person has a different experience, the answer becomes hazy. If it is simplistic and you don’t expect new features to be needed, there’s a good chance. The more complex, the more fixability, scaleability, and extensibility are important, the quicker we get to, ‘sorry, no’. But, this is only for that vibe coding thing.

Lots of people are talking about vibe coding. It is the new hip thing. You give an AI a prompt and the AI spits out code. That sounds amazing . . if it works. Where AI really starts to shine today is as an AI pair. When you have an existing quality codebase on which a skilled software engineer is working, an AI pair is a powerful helper. When one knows how to ask for a very specific addition, then can review and accept code written by the AI, it does supercharge what that engineer can do.

Vibe coding: when you tell an AI what you want and you take whatever code your AI gives you. If the output is wrong or just isn’t good enough, one typically just runs the prompt again or perhaps makes an adjustment. If the new one is still not what you want, try again.

Pair programming: when two developers work together to write code with the expectation that the code will be better than either one could write on their own. It is a collaboration where each dev brings knowledge and skills the other might not have.

AI pair programming: when one of the pair programming developers is an AI. This is not done at the standard prompt. This finds its stride with tools like Windsurf and Cursor. A dev can start with an existing codebase and interact with the AI through a variety of ways from a requirements doc to a simple prompt. The AI generates code, but the dev can now review the code one step at a time, which allows the dev to, hopefully, catch any hallucinations quickly, roll those back, and guide the AI in the correct direction. The dev also ensures the quality of the code, which might include a tweak or a rewrite. Together, they can write much higher quality code than the AI could write on its own and do it much faster than the dev could do on her own. AI pairing will need a post of its own.

If you are looking to build a demo or a quick project that just needs to work for the moment, vibe coding is for you. If you are building a product, find a great software engineer who has a good AI pair and watch them create beauty.