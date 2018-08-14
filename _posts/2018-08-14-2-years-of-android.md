---
title: "What 2 Years of Android Development Have Taught Me"
date: 2018-08-14 10:02:30 -0400
categories: android
---

I still remember the first time I downloaded Android Studio back in October 2016 at Hack Western. All I built that weekend was a simple ToDo app that didn't even really work, but it sparked an interest that would lead me on a 2 year journey that is my android career.
 
 When I first started learning android, I had also just started my degree in software engineering so I was a very inexperience developer. I initially learned independently, none of my other friends did any android development, so I didn't have any real mentor to guide me. This led to a lot of mistakes that I didn't even realize I was making, causing me to waste a lot of time as my side projects grew larger.

 About a year later, I managed to land a competitive internship as an android developer and got paired with an experienced mentor who was able to guide me and help me develop software the right way. Both phases of my development taught me valuable lessons, both on what I should do and what I shouldn't do.

 Hopefully this article will help you get started faster and you will avoid the traps that I initially fell into. Some points will apply to programming in general, and others will be more android focused

### 1. Just Because it Works, Doesn't Mean That it's Good

*"Even bad code can function. But if code isn't clean, it can bring a development organization to its knees." - Robert "Uncle Bob" Martin*

This was the first, and probably the most important things that I learned. Initially, I would name variables my *x* and *y* and didn't care about how I structured my code. These bad practices eventually slowed down every project I did because when I would look at code I had written just a week earlier, I wouldn't have a clue what it was supposed to do.

While code should work as expected, it should also be readable, maintainable, scalable, and testable so that your coworkers can modify your code easily and you minimize the amount of bugs your code can introduce.

I'd recommend checking out Uncle Bob's series [Clean Code](https://cleancoders.com) if you want to improve the quality of your code.

### 2. Pick a Proper Architecture, and Stick to it

Using a proper architecture is a great way to keep your code organized and readable. But many people, even team leads at big companies, will initially choose one architecture, then get hyped up over another one a few months later and start using the new one instead. They are then left with many different architectures being used for different parts of the app, which forces new hires to learn 4 different architectures before they can understand what's going on in the app.

There are many really good architectures to choose from, like MVP, MVC, or my personal favourite MVVM. Before you start writing your app, you should choose one that best fits your needs, and then stick with it. If you don't know what any of these architectures do, this [article](https://academy.realm.io/posts/eric-maxwell-mvc-mvp-and-mvvm-on-android/) does a good job explaining and comparing the three.

(Will be adding more shortly)

### Conclusion

While I am closing this chapter in my development career, many of these lesson can carry over into my data engineering life and to what ever I decide to do after that. I hope someone finds these lessons useful and doesn't make the same mistakes I did.