---
title: Effortless Habit Tracking
draft: false
tags:
  - journaling
  - note-taking
  - focus
  - productivity
  - self help
  - planning
  - goals
  - digital organization
  - mindfulness
  - Obsidian
  - habit tracker
---

#### Planning and reflecting is very important, but habit tracking let's you feel good about your hard work, and be aware of missed days, so you can guarantee long term change.

> “The chains of habit are too weak to be felt until they are too strong to be broken. 
> –Samuel Johnson

## Why Use a Habit Tracker?

### Take It From the Expert James Clear

"If you want to stick with a habit for good, one simple and effective thing you can do is keep a [habit tracker](https://www.baronfig.com/products/clear-habit-journal)."

This is a quote from James Clear who wrote the relatively recent smash hit "Atomic Habits". Don't take the high level advice from me, you should listen to the experts like James. That's why I'm keeping his product link in there, he's an expert so I'm sure his product is great. If you want the full "why?" here's the link to his article: [The Ultimate Habit Tracker Guide: Why and How to Track Your Habits](https://jamesclear.com/habit-tracker). But if you want a free and powerful way to unify your journaling, notes, and habit tracking in one cloud-based solution, continue on. If this is your first Bits and Pieces article, or aren't familiar with [Obsidian](https://obsidian.md/) you may want to start here: [[Effortless Focused Journaling & Note-Taking]]

### TLDR; (Too Long Don't Read)
Habit Tracking gives you clear signals of progress and warnings.
It's benefits boil down to key three points to create positive habits in your life.
1. "It creates a visual cue that reminds you to act."
		Without objective data, we can deceive ourselves.
2. "It is motivating to see the progress you are making. You don’t want to break your streak."
		And it can also help you appreciate hard days.
3. "It feels satisfying to record your success in the moment."
		You'll be less discouraged or overwhelmed by your distance from the end goal.

### What to Track?
I'll put James' examples on a separate page [[Habit Tracker Ideas - Common Daily Habits to Track]].
But the gist is you can be creative, but it's a good idea to start small. Reading 1 page, journaling 1 sentence, exercising or meditating for 1 minute, they're pretty inconsequential, but they're the only impetus you need to become a reading writing 6-packed guru, or whatever it is you want to become. James has a lot of wholesome ideas in there, so do check them out.

### Tips
- Check off your habit as soon as you do it.
- Life happens, it's OK to miss days, just always try not to miss important habits twice and you'll never spiral.
- How long do I need to do this? You don't! "A habit is a lifestyle to be lived, not a finish line to be crossed."

## Let's Setup the [Tracker Plugin](https://github.com/pyrochlore/obsidian-tracker) in [Obsidian](https://obsidian.md/)

### Why? 
#### It's very powerful, simple, and free.
![[Obsidian Habit Tracker Example.png]]

*Powerful*: You don't need all of these features to start, you only need simple calendars. But it can expand with your needs and probably do more than the phone app you downloaded that one time.

*Simple*: The truth is, setting it up might not be, but that's why you're reading this! Once you set it up, you never have to mess with it again, you just open your journal entry, and check off your habits on your computer or phone.

*Free*: Isn't it great when you find free things that are better than the paid thing?
### Download and Activate Obsidian Tracker
1. Open settings by clicking the gear icon in the bottom right:

   ![[Obsidian Gear Icon.png]]
2. Go to "Community plugins" and turn them on: 

	![[Turn on community plugins.png]]
3. Browse the community plugins: 

	![[Browse community plugins.png]]
4. Search for and select the tracker plugin: 

	![[select tracker plugin.png]]
5. Install it: 

	![[install tracker plugin.png]]
6. Enable it:

	![[Enable tracker plugin.png]] 
7.  We setup your daily note template in the [[Effortless Focused Journaling & Note-Taking|last tutorial]]. Here I'm just going to add a simple example, of two habits. In the format "- [ ] Habit 1" to create a checkbox. I put them in a heading with the "#" symbol for "# Heading 1" so I can easily minimize my habit entries when I want to focus on journaling. 

	![[Setup your daily note template.png]]
8. If you have your daily note template setup like in the [[Effortless Focused Journaling & Note-Taking|last tutorial]]:

	![[setup daily note.png]]
	... you'll be able to check off your habits each day you open Obsidian:
	![[habit checkmarks.png]]
9. Now lastly we just need the dashboard. Add this to a dashboard file:
```
tracker
searchType: task.done
searchTarget: Exercise
fixedScale: 1
month:
	mode: annotation
	annotation: 💪🏼🏃🏻‍♂️
	color: "lightgreen"
```
The code in obsidian will look like this:

![[habit tracker code example.png]]

Make sure to include those sets of 3 backticks with the "tracker" word directly after the first set, and you will have added a calendar that highlights any day you checked of "Exercise" in your daily journal. You can change the color and the emoji's to suit your mood:

![[habit tracker calendar example.png]]


10. Want to track streaks? There's code to generate the text for that based on "Exercise" and your "startDate". Surround it with the same 3 ` backticks with word "tracker" in your Obsidian note:

```
tracker
searchType: task.done
searchTarget: Exercise
folder: This is optional if you store your daily notes in a folder
startDate: 2025-02-16
summary:
    template: "Longest Streak: {{maxStreak()}} day(s)\nLongest Breaks: {{maxBreaks()}} day(s)\nLast streak: {{currentStreak()}} day(s)"
```

the code in Obsidian will look like this:

![[habit tracker summary code example.png]]

and it will display like this:

![[habit tracker streak example.png]]

## Quick Start

### Want to Get Started as Quickly as Possible on a Canvas?
I like seeing all my calendars on a canvas that I can move around as I please.
![[habit tracker example 1.png]]

The canvas simple consists of those same blocks of code, but as independent little pages or nodes you can drag around and resize.
### Download that Exact Template Here: 
[[Habit Tracker Dashboard Example.canvas|Habit Tracker Dashboard Example]]
Just add it to your Obsidian with the extension ".canvas".


# Stay Tuned for More Productivity Tips

As we continue this series, we’ll explore tools like the **Motion app** that let you fluidly plan your day, dive deeper into tech philosophy, and help you navigate the world of LLMs. If you enjoyed this post, subscribe below to get notified about new updates. Together, let’s build systems that help us thrive.

[Click here to Subscribe](https://tally.so/r/3x4bR9) and be the first to unlock powerful tips for mastering your habits.