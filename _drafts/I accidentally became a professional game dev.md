Since I was a kid, I dreamed of becoming a game developer. This dream has changed over the years, but I keep holding onto it. I love making games as a form of creative expression and refining ideas to understand what makes something fun. I love creating experiences for others to emotionally connect with something.

When I say professional game developer, I mean somebody who gets paid to make games. And on a strange technicality, I did this.

But let’s start at the beginning. 

### childhood
When I was a kid, video games were seen as a sugary, addictive hobby and was discouraged by my family. I got my own system to play games pretty young, around 8 or 10, but it felt like I was way behind the curve - many of my friends had already been playing for a couple of years at that point.

I don’t know if at the time, I really thought I could be a game developer. But I spent tons of time doing the only thing that I knew how to do - drawing and writing game designs.

I vividly remember reading a particular issue of Nintendo Power magazine over and over when it had a write up on Fire Emblem: Path of Radiance. I never had played a Fire Emblem game before but I fell in love with the promotion mechanics, the RPG stat blocks, and the character designs. I would draft up my own stat blocks, class trees, and draw my own characters with imagined names and backstories.

Eventually, as time passed, I didn’t do this as much anymore, and largely my dreams of being a game developer faded.

### middle school to high school
In middle school, Facebook got big, and I found myself in a similar position: not coding, but drawing detailed product UI designs and writing up press releases for apps I could develop.

I took a web design class around this age using Dreamweaver, but oddly it didn’t evolve into programming and web development skills. I didn’t try much outside of this class.

In high school, I was heavily involved in music, but even then I wasn’t spending a ton of time writing or creating my own music. I was happy “just” playing in the high school orchestra, jazz band, marching band, and a cover band with some friends. 

These days, I wonder what changed between now and then. I’m rarely content without exercising my own novel creativity within hobbies. It’s not enough now to play a song that somebody else wrote.

I did spend many days drawing more and more product designs and UI sketches. I wrote pages and pages of creative writing. This might have been where all my creative energy was going, but still… no coding.

I wanted to create beautiful, novel apps and video games but I was spending my time in the ideation phase, and didn’t have the tools or the knowhow to step into building and tinkering.

### college
My obsession with huge tech companies and web apps drew me to computer science when I started college and it was a seemingly perfect fit. I have had moments since graduating where I wish I pursued a music major, or even a physics major, but I think if I had done that, I would have found that computer science was always another love for me. It ended up the way it did, regardless of how I got here or what other paths were available.

I finally could start to get my ideas on paper into working prototypes with my newfound computer science skills, but I struggled to do so. There were always gaps in my abilities that would place (seemingly) insurmountable hurdles in my path. 

I dabbled in video game development throughout college but again, it never really stuck. I built a choose-your-own-adventure game with a friend for a final project for one of our classes, and I watched a ton of Unity tutorials but I couldn’t quite crack it. I prototyped a game like Life Simulator using what skills I had in Android development, but that effort petered out without a lot of competence in that area.

I took a couple of piano classes in college, and started to write some of my own music in my junior and senior years. This is where my creative energy started to push into.

### post grad
I moved to Berlin and a giant void of social activities (no friends in a new country) led me to spending more time by myself at home. 

After dabbling in Unity for a long time, I finally attended a game jam for the first time. We had only 8 hours to complete a full game, which was incredibly short, even for game jams. I grouped up with a few others that I had never met, and... we built something!

This was my first step into actually developing games and got me over the initial learning curve and hurdles. 

Since then, I've participated in a handful of game jams, built some games with friends, and worked on a couple of solo projects here and there. All of these projects dissipated almost as fast as they started - once they were built they faded into the background.

I had hoped that by this point, I would have created something with a little more longevity. Something that I could publish, be proud of, and come back to. Something that felt "complete". My other projects have been "completed" one way or another, but all feel a bit anticlimactic because they ended due to a game jam time limit being reached, getting sidetracked by other personal projects, or the enthusiasm simply petered out.

### this time around
I've felt tension for a long time about working in software but not working in games. I go back and forth on it... I think I'd be happier, and prouder, to work on video games full time. But I'd most certainly get paid less and be worked much harder. And I don't know if I'd be happy without getting creative control on a game. Would I be *more* frustrated being so close to making games but not being able to make all creative decisions? At least with software development and my day job, I don't dream anymore of creating the next unicorn startup. So I don't mind that I'm mostly just hands that support others accomplishing their dream of being a founder of such a thing.

So, this odd opportunity came about from a couple of stars aligning:
1. Our quarterly "hack week" at work, where engineers are given a week to rapidly prototype and experiment on anything they want.
2. I was in the middle of buying a house and moving, and my manager gave me a free pass to truly do whatever I want - even take it easy and not pressure myself to fully complete something during hack week. If I had nothing to show for at the end of those 5 days, it was no sweat.
3. I have been working through a curriculum with other artists to unblock our creativity.

That week felt like a tailwind. Many of the hurdles that prevented, or otherwise demotivated, me from making a game were gone. I knew that I needed to take ahold of this opportunity and make the most of it. So instead of resting and taking it easy (even with my managers approval, almost encouragement, to do so), I sprung into action and made something, that by many objective standards, has been my most successful game to date.

### the sanctuary
The game I made that week is nothing like I would have expected when I set out to make games several years ago. In my narrow, snap perspective of what kinds of games I would make, I imagined ones that required art, music, physics, logic, challenges, and virtual space.

Instead, my most successful game is a Slack bot. It's text-based. There are no graphics except for emojis. There are no physics or art assets or challenges. I didn't use a game engine - I created a web service.

Let me explain the basics:
1. Users in our company Slack workspace play the game by giving each other emojis as kudos.
2. You can give kudos in a message ("Thanks to @alice for helping me debug a problem"), or by reacting to somebody else's message ("Announcement: I fixed all the bugs")
3. A limited set of emojis (all veggies and fruits) trigger the bot. It tracks every time a user gives somebody else one of those limited emojis.
4. Users can only give out 5 veggie or fruit emojis per day (rather, the bot only tracks the first five).

At the end of the week, users see a summary of who gave out the most kudos to their teammates. It's ideally a way to incentivize recognition for good work.

In order to further incentivize users to engage with this kudo-system, I created a secondary layer to the tool which introduces a fantasy: a virtual animal sanctuary. I think this is what takes my creation from just a tool to an actual game.

The animal sanctuary holds a couple of sick and injured animals. Whenever a user gives another user an emoji for good work, the bot will use that veggie or fruit to "feed" an animal at the sanctuary. The animals grow healthier and stronger, and can eventually be released back out into the wild.

The game is played out over weeks and months. Each animal has multiple steps toward recovery that take a few days of feeding to reach. At the beginning of each week, a summary of the sanctuary is posted in a Slack channel. It shows what animals were fed the most, and provides some flavor text on how the animals are recovering. This is the only narrative or emotional connection to the game. Otherwise it would just be numbers.

### success
Why is this my most successful game? 

1. It has a beginning, middle, and end. There are special cases in the code for starting the sanctuary in the beginning, and there is progression that people are actively contributing to. The end hasn't been coded in yet technically... but I'll add it eventually.
2. It was actually released. Some of my game jam games have been released on itch.io, but not in the same way. That's more of a way of preserving a build, but I haven't shared those widely. This game was *launched* and I had to put some skin in the game when saying that people could start using it immediately. I was at risk of losing face if I had programmed something wrong or didn't expect certain behaviors.
3. People actually play it. And not just people I asked to play it for testing purposes. I presented the game at the end of the week, but not everybody in the company saw this presentation. They simply noticed the tool in Slack, started to use it, and were able to be introduced into the game.
4. I got to tap into real experiences I've had and express myself. Animals at the sanctuary are based off of individual animals I know and love, or species that I adore and admire. I saw a blind mouse in a field one time, and I turned that experience into an expression that other people can tap into and relate with. There are basically 0 other projects I've worked on where I can say that.
5. I got paid for it, somehow!

The thing that boggles my mind the most is that this was *enabled* by my full-time day job. I was so convinced that my full-time day job *prevents* me from creating games, and here it was providing me a safe place to create something. And I was able to meet a real peak in my creative journey.

### what happened?
From nine to five, a certain voice in my head is largely silent. It knows it has nothing to say because I don't care *too* much about what goes on in between those hours. I want my work to be high quality, yes, but I don't identify with it. As soon as I start to identify with something, this voice starts to pipe up.

This voice tells me that I'm not pushing myself hard enough. That if something is easy for me, I can't be proud of it. That if I want to make something good, I have to suffer for it. This voice makes itself a cornerstone to every project I work on. It *must* be involved otherwise the thing that I make will be shit. And it stops me in my tracks, prevents me from making any progress.

Somehow, this game snuck past this voice, and it only noticed at the end of the week after I came out of my trance. I realized what I had done, and I dispelled a powerful myth without even meaning to: I made something great, and it wasn't even really that hard for me. I was the proudest of something that played to my strengths, instead of only feeling proud of overcoming some great obstacle. Of fighting to make games with skills that are unrefined and uneducated. I used the skills that I spend every day honing, and was able to still find a pocket where I can be creative and make art. 
