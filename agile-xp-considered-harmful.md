---
title: On agile/XP being considered harmful
---
# On agile/XP being considered harmful

This is my answer to the whole conundrum explained in this article: [https://retrosight.github.io/learning/why-agile-xp-so-often-fails-heterogenous-teams-sarah-mei.html](https://retrosight.github.io/learning/why-agile-xp-so-often-fails-heterogenous-teams-sarah-mei.html)

I'll also try to answer some criticisms I got from friends on twitter.

I'm going to try to make two points in the clearest way possible. I'll try to tone down my sarcasm to a minimum.

My main point is similar to what Uncle Bob said. The premises in the article are mistaken, making the conclusion inevitably absurd.

My secondary point is that almost everything that was said against the article everywhere I saw was misinterpreted by its proponents. In part, the problem is that complex ideas are hard to be expressed in a short tweet. Another reason is that "liberals" (in the American sense) usually have a much worse grasp on conservative ideas than the vice-versa. This fact has even been [verified scientifically](http://www.theamericanconservative.com/2012/12/13/open-minded-conservatives-prejudiced-liberals/).

## 1. Mei's article analysis

Here are some claims that she exposes at the beginning of the article, and supposedly will be demonstrated its end.

1. Agile/XP doesn't work in heterogeneous teams.
2. The reason behind claim #1 is because of the race and gender (ie, "white men") of Agile/XP creators.
3. "The practices assume the practitioners all have A LOT of built-in privilege."

Throughout the article, she cover two of the practices. First, Pairing, then TDD. Fair enough. Let's see if her argument holds water.

### On "power dynamics" and hierarchies

The fundamental premise that she makes on her deconstruction of Pairing and TDD is the concept of "power dynamics". Let's dive into that in isolation first. Here is her own explanation of what this concept consists of.

> A power dynamic is behavior in an interaction driven by a hierarchical relationship between the participants. This hierarchical relationship can be formal (manager-report, or senior-junior) but more often is informal (based on race, gender, background, etc.).
> 
> Men are more powerful than other genders; white people are more powerful than other races. And so forth.
> 
> Common power dynamics in play in a pair programming situation (low - high):
> 
> - junior - senior
> - “wrong” background - “right” background
> - learning developer - teaching developer
> - feminine - masculine
> - people of color - white folks
> - women & other genders - men
> 
> The list above is a good start, but there are many others: national origin, native language, external signs of religion, editor preference…

She also implies that, when someone "places themselves above" someone else, then the first person is in the "upward" side of a power dynamic. Apparently, one's position depends both on immutable characteristics and his/her actions.

I think the fundamental principle behind this concept is correct. Hierarchies do exist. More than that, I assert that they are _inevitable_. The formal ones are easily identifiable. The informal ones are harder to see, but they are there. One natural phenomenon in human groups is the emergence of informal leaders. Peers can fare better or worse than others due to a whole array of traits.

The traits she listed as influencing one's "power" can be but in two big buckets.

1. _Competence_ traits: For example, a senior is usually more competent than a junior; a native speaker of the language being used will probably communicate with more competence than the non-native speaker. It's self-evident how these traits make one get higher in the hierarchy.
2. _Superficial_* traits: The most glaring examples are race and gender. Religion, marital status, and tastes in general would also fall into this bucket. The case for "power" disparity in each of this traits is not self-evident at all. Each of them must, therefore, be carefully measured.

`*` I couldn't think of a better name for this bucket. Please, bear with me.

One important fact to have in mind is the difference between correlation and causation. For example, let's assume tall people fare better than short people. The correlation was measured. The causation is not clear. It could be we generally have a bias in favour of tall people. It could also be that tall people usually were better fed when they were young, meaning that they are also healthier, on average. It could also be both.

A second important fact is that context matters for any trait difference. For example, a child will probably beat a basketball player when the game is hide and seek.

Having this in mind, let's proceed to the practices being analysed.

### Pair programming

Here are some the premises she makes about pair programming that I fully agree with. These are almost obvious to anyone that tried pairing in extreme schedules.

1. Very few people can pair 8 hours a day.
2. Many people can’t do a 9-6 fixed schedule.
3. Many people have motivators that don’t mesh well with this system, including pushing frontiers via more research-y code, being in solo ‘flow,’ & using new technology.
4. Full-time pairing is hard across time zones. Having everyone in the same time zone is often unrealistic.

Her fundamental premise about pairing is that "[people that can't pair that much] are all usually on the downward side of one or power dynamics in their pairs."

She claims that "the folks on the downside of those dynamics when they pair program feel constantly watched, judged, and steamrolled" and that they don't "feel empowered to contribute", causing them to not be able to pair that much. The case for that is wanting. Let's consider a few different situations.

First, a hypothetical pair where the only difference is their _competence_ traits. The level of contribution of each person will obviously be different. Now, is that a problem? Not at all. The more competent will inevitably produce more, and the less competent has a chance to learn. Now, of course, the less competent can be shut down, even if he/she has some good ideas. For these bad pairing situation to happen, it's necessary that other traits come into play. One side might be impatient or rude. There might be some lack of trust. The assertion that the competence difference alone would cause a bad situation is clearly false. The opposite is actually true. Competence diversity in a team makes the whole team more competent overall. And pairing is a great technique to spread the diversity of knowledge.

Now, what if the difference is in a _superficial_ trait. Maybe, the two have different circadian cycles, and one is more alert while the other tired. Maybe, one has to leave early to take care of his/her children. These indeed would make pairing difficult. But is it true for every possible _superficial_ trait? Mei incorrectly assumes so. Her defenders insist that the fact that she is a woman makes an authority about woman oppression. In her defense, I don't think she used this reasoning herself. She simply asserts she's right about this. What is extremely *ironical* is that she clearly says that pairing works really well with her brain. Her personal experience with pairing is a counter-example to her own theory!

Please, note that _I'm not claiming that there's no oppression of women during pairing_. What I'm saying is that Mei fails to prove that this is true. She simply jumps from the premise that women are oppressed in general (which is also debatable) to the conclusion that they are oppressed during pairing. There's not even an attempt to demonstrate this logical jump. There's an equivalent mistake for race.

#### Mei's solutions to the pairing power inequality

As I showed, her case to show that the power inequality is a problem during pairing is flawed. Consequently, her proposed solutions are based in wrong assumptions. I shouldn't need to, but I'll analyse those anyway.

Her basic proposition is that "power dynamics are something EVERYONE has to keep in mind" and "take real action to level the playing field".

If the root of the problem is that one person is rude or bigoted, I'm completely with her. Pairing demands respect from both parts. Now, if the difference is in competence, she's wrong. Just imagine this situation. You are undergoing a complex surgery. There are two doctors, one expert and one junior. Would you want a "level playing field" there? Would you want both doctors to have the same say as to where to cut you? I doubt it.

She goes further and propose the following specific actions to be taken.

1. "The more dynamics you’re on the upward side of, the more you take cues from your pair."
	- Translation: the more you think the other person is below you, the more you should patronize them. I abhor this idea. I'd rather be respectful, and strive to treat everyone as if they were capable to teach me something, even if the subject at hand is completely out of their league.

2. "Think ahead of time of what dynamics might exist, and think carefully about where you are relative to each other in those dynamics."
	- Translation: always be mindful of every superficial trait of the other person, especially race and gender. It's the typical reasoning behind [bankrupt ideas like affirmative action](https://www.hoover.org/research/affirmative-action-around-world). I prefer to learn my teammates personal idiosyncrasies, and adapt my way of pairing so that we work in a productive and amiable way. 

3. "When your pair doesn’t reciprocate (i.e., talks over you, thinks their way is always correct, has reactions that would be different with someone else), one way to neutralize that is to demonstrate a power dynamic where you’re on the upward side, & they’re on the downward side."
	- Translation: when you feel oppressed, hit back. This is utterly detestable. What happened to giving honest feedback and being respectful? Regardless if the more "powerful" person is being bad on purpose or not, lashing out will likely make the situation even worse. When there's no real oppression, but only a competence difference, a good advice is to be humble, and try to learn something. Ask questions instead of demanding to be heard.

### TDD

Let's analyse her case about TDD. I confess that she raised a very interesting case here. According to her, men prefer a "bullet point" strategy for writing tests and women prefer a "narrative" strategy. As someone that is quite fond of the art of writing tests, I'm honestly curious about her own strategy. I'd probably love to pair with her. Unless she tries to "neutralize the power dynamic" with those absurd rules listed above, of course.

I was dissapointed to see that her evidence of the "bullet point" vs "narrative" difference is no more than saying that "current research" and "science confirms" it. Again, she could very well be correct. Yet, no evicence is offered apart from her own experience.

She asserts that TDD itself is broken because it defends the male "bullet point" approach as the "right way". How is this part of extreme programming is a question she doesn't answer. Just because some approach is thought as the "right way" by a majority, it doesn't mean that the practice itself is broken. As a contrarian myself, I'm always skeptical of that the majority thinks. And [XP actually encourages](http://www.extremeprogramming.org/rules/fixit.html) this openness to review the process.

Her frustration with this fight to push the "narrative" approach puzzles me. I personally have some strong opinions about testing, and many times it conflicts with everyone else in the team. Instead of feeling oppressed, I feel extremely empowered. It's like having access to one insight that no one else gets. Those are exactly the situation that earn me promotions and raises. Naturally, I don't expect that the idea will be accepted only because of my oppression status. I have to work hard to sell it, and then let the intrinsic value of the idea itself show that I was right after all.

### Her answers to criticisms

She finishes the article with a few reactions to her ideas, and asserts that they "all explicitly or implicitly say I’m fabricating these differences". Then she concludes basically implying that whoever disagrees with her premises should be shut out, using an incredibly ironical GIF of a *boy* pushing a *girl* out of a house.

I assert that her reaction was such because she did not understand what her critics were saying. And that brings be to the second part of my own article.

## 2. On Communication Impedance

Here are a few example of comments directed to me and people my side side of this argument.

- "You talk as if I’m denouncing or incriminating someone"
- "Trying to dismiss the fight of those who aren't as lucky"
- "someone who has a different experience says that they are factually wrong"
- "this discussions is not about agile or about people lives and how to improve them, it's about ideology and playing argument-king"
- I'm pretending to "know it all" and that I'm "better than everyone else"
- "how winning arguments on the internet is important to you"
- "blindness in thinking that Agile/XP is perfect the way it is"
- "The problem is that you've been using it as a hammer and with an air of superiority."
- "why it’s so important to be conservative about it?"
- "And why?"

For anyone that read carefully what I wrote, it should be clear that the people that wrote the messages above failed to understand what I'm talking about. In all fairness, this is also my fault. The dissection of Mei's text I did above is one way I'm trying to clarify the whole matter. Let me try to go further.

Beware that the things I'm about to say will be harsh. Excuse me for my bluntness. I mean no personal disrespect at all. The criticisms below fully apply to me when I was younger.

In the conversation online, I might be guilty of arrogance; of abusing sarcasm; of trying to too hard to simply prove that I'm right. This is a matter of my flawed style, though. I believe that, with few exceptions, people on both sides of the debate are attempting a similar thing. We want to expose our ideas because we think they are better. There's hope some bystander will "learn something". Just budging the more opinionated on the other side would be a victory. Sadly, the problem is deeper than that. In my own experience, including the comments listed above, and [science](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0050092), there's a large asymmetry in how much one side can even understand the ideas from the other side. I won't try to explain the reason behind this. I'm just observing that it is indeed true. Let me delve into the implications of this fact.

First, there is the persistent incapability of progressives (in the lack of a better word) to perceive the diversity of opinion of the people that disagree with them. The truth is that there "left" is much less diverse in opinions than the "right". The "right" is so diverse and full of rifts that it is not by any means a political group. Here's Gavin McInnes in 2016 listing [14 Different Groups on the Right Wing](https://www.youtube.com/watch?v=EXs879mUu4o). Naturally, I'd make a different list. I'm definitely not in the same group as Gavin. Hopefully, you got the point. 

A more disturbing implication is illustrated by the last list item above. "Why?", they ask. After failing to understand _what_ we are saying, they start to wonder how is it even possible that we reached such irrational conclusions. Maybe, we are blinded by ideology. Or perhaps it's worse. It's our intentions. The only reason _why_ we disagree is because we don't care about the suffering of the oppressed. Many will hold this thought in disbelief and ask us "why?". Others, start believing it, then they curse us, then ignore us, then block us, both online and in real life. For the ones still reading, let me tell you something. You couldn't be more wrong about this. To prove that let me address one last point.

### On Individualism

Once, in a bar, this acquaintance of mine asked me a straight question: "Are you an individualist?" I knew exactly were that was going, but I answered "Yes", full stop. He looked at me like I had said that I eat babies hearts for breakfast. He stormed out, and unfriended my on Facebook probably at the night. I never got to learn what kind of monster he imagines individualists are.

Of couse, I agree that we all do categorizations all the time, and that categorizations come with bias. It's a two-edged sword, as Daniel Kahneman explains in [Thinking, Fast and Slow](https://en.wikipedia.org/wiki/Thinking,_Fast_and_Slow). It can be both useful or hurtful. People that fail to understand what individualists believe tend to think that we deny this human instinct. Or, if we don't deny it, we simply do not care about the unfairness that it might create. That's wrong. No one denies that bias exist. And I don't know a single person that doesn't care about the unfairness problem.

So, what do individualists defend? The traditional western way way of dealing with this problem is be emphasising the idea of equality under the law. Both Common Law and Civil/Roman Law share this feature. Aphorisms like "all men are created equal" (that includes women, btw) and "justice is blind" are reflections of it. The principle is to treat individuals solely by their actions and not by whichever categorizations they fit in. Naturally, there were discrepancies like the Apartheid and Jim Crow laws. Those are corruptions of of  the principle of equality under the law, that permeated legal system because they are inevitably written by flawed humans.

Individualism is this almost uniquely western tradition, condensed on that simple principle.

One counter-argument is that it's idealistic for people to people to treat everyone as individuals. Even though this assertion is correct, it doesn't mean that we shouldn't try. In the case of pair programming, how many people can a programmer pairs with on a regular basis? Half a dozen? Is it seriously too much to ask to each one of these coworkers as individuals? I don't think so.

Another counter-argument is about historical oppression, and that the only way to correct it is by "affirmative action". I'll recommend Thomas Sowell's work again. Regardless of the intentions, the empirical evidence shows that [affirmative action consistently makes matters worse](https://www.goodreads.com/book/show/1139178.Affirmative_Action_Around_the_World) in many ways.

The ideas that Sarah Wei defends go in direct opposition with individualism. In order to balance our biased unfair categorizations, she proposes more categorization. Racism should be solve with more racism and sexist with more sexism. It's a distributed form of affirmative action, bound to only foster more resentment and division. It's the infamous bigotry of low expectations. She firmly defends that large groups of people are unable to rise up by themselves without some handout. Ironically, she explains her success on her own merit, despite being a woman. She's probably more influential than 99% of other programmers. Paraphrasing Jordan Peterson, all power to her, as far as I'm concerned.

## Conclusion

To everyone out there that might be under the impression that I'm a monster, I hope you can have a much more nuanced image now. All I ask is that you try to understand what I'm saying before assuming that I'm what I'm not. You may or may not have thought that this whole text was an attempt to show some moral superiority. It is not. I'm not saying I'm morally superior. I'm simply saying that you are wrong.

For those that still think I'm a monster and don't want to talk to me ever again, so be it. For those that respectfully disagree and want to have a conversation, my door will always be open. Perhaps, you'll be able to change my mind.
