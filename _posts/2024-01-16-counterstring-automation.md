---
layout: post
title:  "What Is Test Automation Really?"
date:   2024-01-16
categories: Automation Tools Testing
comments: false
---
When I started in QA as an apprentice, I did the course and the final project, and got the ISTQB foundation qualification along the way.
The course taught and assessed around the ISTQB format and definition of testing, write test cases with defined steps and all the other 'necessary' documentation before executing the predefined tests.

Portraying testing as a *just* defining some repeatable steps and checking outputs is one big reason why automated testing tools can be largely overvalued as replacements for human 'manual' testers. This was a realisation made possible by voices supporting a context-dependent approach to 'automation' and how it is better to discuss 'test tools' instead. <!--more--> Making this switch changes the notion of 'automation in testing' to cover all aspects of testing. Tools are used for test design, test execution, test reporting, and more. [1]

While considering test tools and my own testing approach I came across 'counterstrings'. This is a text block which self describes its character count at intervals with a number indicating the position of a marker character (e.g. a counter string of length 10 would be \*3\*5\*7\*10*). [2]

It can now be said that my 'automation journey' started much earlier than I first thought as, despite other better, free, and more feature-full tools available for the same job, I made my own counterstring generator. [3]

It was a very simple console app written in python but I still use it after many years for testing fields and inputs. Who knew I was automating parts of my testing all along?

###### Notes/References:

[1] The main motivation behind this was a collaborative work by James Bach and Michael Bolton in a combined paper ([here](https://www.satisfice.com/download/a-context-driven-approach-to-automation-in-testing)) and related blog posts such as [this](https://developsense.com/blog/2023/01/test-tools).

[2] I first was introduced to counterstrings in a video by The Evil Tester, Alan Richardson ([here](https://www.youtube.com/watch?v=-Cs80GWeRuY)) however this idea is credited again to James Bach ([here](https://www.satisfice.com/blog/archives/22)).

[3] A list of my projects, including the counterstring tool, can be found [here](https://sampeas.github.io/projects/). Alternatively, go straight to the GitHub repository ([here](https://github.com/sampeas/python-counterstring-generator)).
