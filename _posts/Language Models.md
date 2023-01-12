---
layout: post
title: "AI and Language Models"
description: "test description"
tags: AI, Economics
date: 01/04/2023
---
 
 
In high school, I toured a local engineering college and, on the tour, I listened to an excited student demonstrate his research project. "What we are learning in this class," he said, "is at the forefront of a field called Artificial Intelligence, or AI." The project was a game where two opponents competed to capture white or black squares on a basic grid. The computer opponent would "learn" from each round to improve its strategy in the next game. In the demonstration, I watched these bulky squares meander across the grid. This was in an era before hashtags, but my reaction of #notimpressed sums it up pretty well.
 
This just didn't seem useful. I'd grown up reading sci fi filled with Artificial Intelligences, and they could have captured this whole grid while also cooking your lunch and navigating a spacehship. At the time, I did not appreciate the steps needed to get from a primitive AI like this game to something more world shaking.
 
But now we are at a time when it seems new AI breakthroughs are happening every couple of weeks. Later posts will consider what may coming in the next few decades, but for now, this is a brief review of the current state of language and image AI tech as of January 2023.
 
I'll first look at capabilities of these models, and then do my best to explain how they work. I'm not involved in AI in any way, so my understanding of this is all roughly at the "AI village idiot" level. Please correct me if you find any major errors!
 
**Large Language Models - ChatGPT**
[ChatGPT](/https://chat.openai.com/chat) is a Large Language Model (LLM) developed by OpenAI, a leading AI research firm. Principal cofounders include Elon Musk and Sam Altman, both tech startup luminaries. The ostensible goal of the founders was to create a company that would share the bounty of strong AI with all of humanity. We'll see how that goes.
 
ChatGPT is merely the most recent of several notable LLM of the past couple of years. I expect LLMs to continue improving, with new models released frequently. To help with evaluating progress over time, I've selected a few prompts that I will give verbatim to different LLMs, and we can see how the responses improve. Below, I'll show the prompt in **bold**.
 
**I am planning three fancy dinners. Each dinner should have four courses, with each course featuring a common ingredient. Please provide menus for each meal, including wine or beer pairing, in a bulleted list. Include the total calorie count for each meal.**
 
*Here are three menus for fancy dinners with four courses, each featuring a common ingredient. I've also included suggestions for wine or beer pairings. The calorie counts are approximate and will vary based on the specific ingredients and portions used.
 
Menu 1 (approx. 1,400 calories):
- First course: Butternut squash soup with toasted pumpkin seeds (200 calories)
  - Wine pairing: Chardonnay
- Second course: Salad with mixed greens, pears, and blue cheese, dressed with pear vinaigrette (200 calories)
  - Wine pairing: Riesling
- Third course: Roasted pork tenderloin with caramelized pears and mashed sweet potatoes (500 calories)
  - Wine pairing: Pinot Noir
- Fourth course: Spiced pear tarte tatin with vanilla bean ice cream (500 calories)
  - Wine pairing: Late Harvest Riesling
 
Menu 2 (approx. 1,500 calories):
- First course: Grilled romaine lettuce with avocado and grapefruit dressing (200 calories)
  - Wine pairing: Sauvignon Blanc
- Second course: Crab cakes with grapefruit remoulade (400 calories)
  - Wine pairing: Chardonnay
- Third course: Grilled shrimp with grapefruit and fennel salad (400 calories)
  - Wine pairing: Rosé
- Fourth course: Grapefruit panna cotta with mint sugar (500 calories)
  - Wine pairing: Moscato d'Asti
 
Menu 3 (approx. 1,600 calories):
- First course: Tomato and basil bruschetta (200 calories)
  - Wine pairing: Pinot Grigio
- Second course: Arugula and peach salad with balsamic vinaigrette (200 calories)
  - Wine pairing: Prosecco
- Third course: Grilled chicken with peach chutney and wild rice (400 calories)
  - Wine pairing: Viognier
- Fourth course: Peach crostata with vanilla cream (600 calories)
  - Wine pairing: Moscato d'Asti
I hope these menus inspire you to create your own fancy dinners! Remember to always drink responsibly and to adjust portion sizes to suit your individual calorie needs.*
 
**Pretend that J. K. Rowling has decided to write a new Harry Potter novella, taking place four years after Lord Voldemort was defeated. This story revolves around a difficult heist, planned by Ron. Suggest a plot that might be used for this story.**
 
*Sure, here's a plot suggestion for a Harry Potter novella set four years after Lord Voldemort was defeated, with a heist planned by Ron:
 
It's been four years since Harry defeated Lord Voldemort and peace has finally been restored to the wizarding world. Ron Weasley is now married to Hermione Granger and they have two young children together.
 
Ron has always dreamed of being a successful Auror, but despite his bravery and determination, he has struggled to rise through the ranks. Frustrated and feeling undervalued, Ron hatches a plan to pull off a daring heist and prove his worth.
 
He enlists Harry, Ginny, and Hermione to help him steal a valuable and powerful magical artifact from the high-security vaults of Gringotts Wizarding Bank. The heist will be risky and require all of their skills and cunning, but Ron is determined to succeed.
 
As they plan and execute the heist, they must also deal with unexpected complications and confront old enemies who are determined to stop them. Can they pull off the heist and come out on top, or will their plan fall apart and land them in hot water?*
 
**The New Yorker is considering a story comparing the first person to use hieroglyphics with Banksy. Suggest the first three paragraphs of a possible story.**
 
*It is interesting to consider the similarities between the first known user of hieroglyphics and the contemporary artist known as Banksy. Both have made a significant impact on the world of art and have managed to maintain a level of anonymity that has only added to their mystique.
 
The first known user of hieroglyphics was a scribe named Nasa, who lived in ancient Egypt around 3200 BC. Nasa was a highly skilled writer who used hieroglyphics, a system of writing that used pictures and symbols, to record the history and culture of the time. Despite his importance in documenting the civilization, little is known about Nasa beyond his role as a scribe.
 
Banksy, on the other hand, is a modern-day artist whose identity remains shrouded in mystery. Active since the 1990s, Banksy has gained international fame for his street art, which often contains political and social commentary. Like Nasa, Banksy has left a lasting mark on the art world, but unlike Nasa, Banksy has carefully cultivated an air of mystery and anonymity around his identity.*
 
These are all pretty good, although the third example reveals some weaknesses. Nasa is introduced as the first user of hieroglyphics, but no such person existed. Ask ChatGPT to answer factual questions, and not knowing the answer will not slow it down. ChatGPT will make something up that sounds convincing, and currently doesn't give any indication that it is misleading. This is a bit risky, kind of like riding in a self-driving car that hasn't had all the kinks worked out. ChatGPT can be humming along, telling you all sorts of facts about the origin of spiced pear tarte tatin, when BAM! it takes a wrong turn into Japanese cuisine, without you ever realizing it.
 
In future posts, I'll take a look at the current state of image generation models, and also try to develop an understanding of how these things actually work. For now, this is long enough so I've asked ChatGPT to provide the closing to this post. Here you go: Welcome to my blog, where I'll be sharing my thoughts, experiences, and insights on a variety of topics, I hope you will join me on this journey of self-discovery and growth.
