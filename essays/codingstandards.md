---
layout: essay
type: essay
title: "Some Coding Standards Suck"
# All dates must be YYYY-MM-DD format!
date: 2025-02-8
published: false
labels:
  - Coding Standards
---

//img

This week we went throughand learned about the importance of coding standards, and specifically in  ICS 311, we were forced to use their own specific coding standard for all of our projects so far. Personally, I agree with what a coding standard is. It is a way for people to collectively get together and agree on how code should be written so that everybody else can easily read it, but with this standard that I have gotten in class has really annoyed me and wasted whole *minutes* of my time so far in these assignments.

##Nitpicking About Coding Standards

There are some things in these standards that I don't see the purpose of. The first and worst thing is the fact that the program would refuse to boot when the code is not following the coding standard. Not only is it annoying in general when the code would work anyways, but it also is annoying because of the various rules, and I am not talking about rules that would genuinely make the code unreadable like this: 

```Javascript
let output = 0;for(let x=0;x<10;x++){output=output+(A[x])}
```

It's the very specific things ike this:

```Javascript

function func(){
}

```

This is wrong, in fact this code is so wrong the code will not even compile for you to run. According to the coding standard, this is what good code is:

```Javascript

function func() {   //I PUT A SPACE HERE
}

```

Yes, of course putting a space between the parentheses and curly brace is *needed* to have the code be absolutely readable. 

I understand this though in a way, being able to have a uniform way of coding for the sake of having things be easily readable is perfectly fine. But there is one specific rule that wastes my time the most that I absolutely don't understand.

## 2 spaces vs tab

When I code, I press tab to indent so that I can more easily read my code. This works with others as well, as pressing one button per indent is enough for others to see the amount of space being made. So why in this coding standard is it required to have two spaces per indent instead?


```Javascript

function func() {
  indent
  2 spaces
}

```

I don't even think there is a difference between the two when you glace at code, but one method of indenting requires *200%* of the effort to do. Why do I need to double space? It is statistically more viable to instead use tab, but the standard does not want you to do that.
