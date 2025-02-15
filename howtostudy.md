# How to Study Computer Science  <br />A primer for COSC 101 at Colgate University

by [Prof. John Stratton](http://cs.whitman.edu/~strattja/)



## Introduction

Whether you are an ambitious student reading this before the term starts,
a dutiful student reading this after your instructor told you to, or a
stressed student trying to figure out how to get yourself unstuck from what
feels like a mental block, welcome to this guide!  This guide was written for
you, condensing some of the practical advice that has come out of many hours
of conversations with students in my office.

Computer Science is... unusual. Think about other fields in the natural
sciences. In high school, almost every student intending to major in physics
had several high-school physics classes. Same for chemistry, biology, and
math. Majors like neuroscience are a bit different, but basic science courses
like chemistry and biology are still pretty good preparation. This is true
beyond the natural sciences as well. In many fields, adequate preparation in
critical reading, analytical writing, and common high-school subjects smooth
the transition into courses on humanities and social sciences.

It is unfortunate that, in the United States, despite Computer Science being
an increasingly important field to our culture and economy, very few high-school
students have access to high-quality introductory computer science courses.
When you arrive in COSC 101, you will have two big challenges - learning a
second language, the language of algorithms and specifically the Python
dialect. On top of that, you will have to learn problem-solving skills that
are more about learning creativity and design than learning facts. That's a
big challenge, and the strategies you may have developed to learn other
materials may not work out as well in this class.

This primer is an attempt to not leave you alone in figuring out how to learn
what we're trying to teach you. With homework and labs, you will get quick
and good feedback about the artifacts of your effort. What you might not get
feedback on as easily are the habits and methods you used to do your work,
because we can't see that as easily to give that feedback. Your lab
instructors will try, but it's hard to see everything in a class of 14-16,
especially when many of the things we'd like to give feedback on are what
happens when you're specifically not talking with us or asking questions.

Every person is unique, and much of what is in this manual might not apply to
you. However, if you feel like you are struggling, putting in a huge amount
of time for what seems like a relatively small amount of progress, or you just
want to get more out of this course, there is a good chance that in some of
these sections, you'll see a mirror image of yourself. And that's because
for almost every challenge you have faced, your predecessors have also faced
that challenge, they talked with me about them, and I had some advice that I
hope was useful to them, and will be useful to you now.

Welcome to the wonderful world of CS 101. Here are my best tips and tricks
for passing like a superstar.

## Types of Mastery

I'm sorry. One class isn't going to make you an expert programmer. Actually,
I'm not really sorry - the fact that you can't become an expert programmer in
one class means that all of my former students have reasonably secure jobs.
However, you don't have to be an expert programmer to be able to write some
pretty powerful programs and solve a lot of problems, just as you don't need
to be an expert carpenter to be pretty good at DIY home repairs. However,
you will need some tools and the knowledge of how to use them, and that's
what this course is about.

When people are gaining new knowledge, educators sometimes talk about "levels
of mastery", where students start out with no mastery, and gradually become
more and more familiar with the material. The ultimate goal is deeply
understanding a new idea well enough that you can see a new situation and
make good, informed decisions on how that idea might apply to the new
situation, comparing it with many other ideas and making good choices about
which ideas is most valuable in describing or solving that situation.
Several scholars have even proposed formal taxonomies and stages of learning.
But you're not an educational psycologist, and I'm not convinced that you will
experience a linear progression among the different sub-skills that go into
being able to write programs. So we're just going to focus on
what you're likely to experience in the lab and homework assignments.

#### "What does this even mean?"
When you're first shown new ideas or new approaches, you'll have the
opportunity to just try them out. It's new, so just by looking at a piece
of code, you're not going to know what it does or why. Even if you've been
shown exactly what you would need to know to understand what it does and why,
you won't have digested it yet, and that's fine. Your goal, when starting
out with new material, is to play with it. Take the examples from lab, type
some stuff, and use the interpreter to see what it does.

#### "I understand what this does"
After you have learned the basic concepts for a certain programming tool,
the best thing you can do is look at examples of how the tool can be used.
The solutions to lecture examples and your own solutions to lab and homework
assignments are all examples you can learn from, and will help your mind
recall patterns. Then, when you see a new problem, you are more likely to
be able to recall a similar problem you saw before, and the similar solution
that went with it.

#### "I have an idea of how to solve this, but I'm not sure"
In this course, you will often be asked to practice new skills though being
given problems that require you to use those skills to solve. Sometimes,
you will be able to remember and see the connections between examples you have
already seen and the solutions that went with them. Even if you don't,
remember that the problems you are given are not random. Even if the
assignment doesn't spell it out or look familiar, you should always be
thinking along the lines of "how can what we just learned in class be used
to solve this problem?"  You might not know right away, but the important
thing is to try something. You will probably get it wrong several times before
you get it right, but that's okay. The worst thing that can happen to you
when you get a new problem is to try nothing because you are not convinced
that what you're thinking of will work. Many students get their first working
solutions not by knowing exactly what to do, but by writing something,
anything, and then fiddling with it until it works.

The most common place that I have seen students get caught is here, because
not knowing exactly what to do, writing something, and fiddling with it until
it works is a reasonable strategy for completing the assignment successfully
and getting a good grade on that assignment. But beware, it can be a trap if
you think that because you got working code in the end you have learned
everything you needed to. Fiddling with code without understanding it may
get you through labs, and even some of the homework assignments, but will
fail you on the exams where you don't have an interpreter to help you fiddle
with your code. Also, even for homework assignments, code-fiddling is a very
inefficient way of getting things done. The course builds on itself, so while
it might be okay to spend an hour or two fiddling with the one loop in an early
homework assignment, later assignments will include many loops. So, you will
need to learn to master each topic well enough that, eventually, you can apply
it in a solution quickly. That is what the later sections will help you do.

#### "I know what this should do"
Now that you know the rules of algorithms and Python in general, you should
be able to beat the interpreter. The interpreter isn't generally wrong, but
if you're always asking the interpreter to tell you what your code is doing,
you're missing a step. Once you feel like you "understand" a concept or an
idea, take an example piece of code and try to predict what will happen when
the interpreter runs. Where do these examples come from?  Well, there will be
some in lecture, but those are probably a bit early for you to really get the
most out of them. The best examples are your own works-in-progress, when
you have some code written for an assignment, you're pretty sure it's not
finished, but who cares?  Stop yourself before you run the interpreter to see
if you can predict what will happen when the interpreter runs. If your
prediction is wrong, can you see what you read or thought incorrectly?  Keep
trying, until you can more often than not successfully predict what a piece of
code will do when the interpreter takes it.

The reason many students do not practice this way is because, at first, it is
slower than just asking the interpreter what your code does. But there are
two reasons why this practice is important. First, every exam will start with
several problems like this, where you have to read a piece of code and report
what will happen when it runs. Second, it will force you to understand the
code more deeply than you did before. When you look at examples of working
solutions, you already know what the program does, which leads many people to
not pay as close attention to every detail of how it works.

This practice will not come naturally to you, but will reveal gaps in your
understanding you may not have noticed otherwise, and will greatly increase
your understanding and success on the relevant sections of the exams.

#### "If I change this..."
Now that you can read a piece of code and understand what it does, now start
thinking about variations. What would happen if you changed one part or
another?  This level of knowledge and kind of exercise is very similar to those
in the previous section, but begins to put your improved understanding of how
code works to practical use.

There are two ways to predict the effect of a change. One is to make the
change, and then reanalyze the new code fresh to see what it does. But this
is inefficient, and by going through this practice you will naturally start
to develop the second method, which is to understand the original code well
enough that you understand the role and effect of the thing you plan to change.
If you understand how that part fits into the whole, you can quickly narrow
down to the precise differences in the code's behavior based on the change,
quickly screening out everything else that is unchanged in both the code text
and the code's behavior. This is a much deeper level of understanding that
will also help you write new code much more quickly and correctly, both in
future homework assignments and on exams.

#### "I can fix this"
Many students spend the vast majority of their homework time debugging.
The ultimate goal of the previous steps is to help you come up with solutions
more quickly that are less likely to have bugs in the first place.
Bugs still happen, though, to everybody, and the same skills that help you
avoid bugs in the first place will help you find and correct them. By
understanding how the various pieces of your program work and interact
together, you will be more able to identify what part of the code is most
likely responsible for a particular error. That same understanding will then
help you reexamine that piece of code to identify what it might be doing
incorrectly, and the exact change needed to correct the mistake.

## Getting Help
If you read through the previous chapter, it should be clear to you that, at
the beginning of learning a new concept, there will be a lot that you cannot
do for yourself. At first, debugging, understanding of the different pieces,
and even just knowing what a bit of code actually does will be beyond you, and
yet you have an assignment that requires those skills to get through it.
This is why the course is extremely well supported with around a 5:1
student to lab tutor ratio in each lab section, supervised open lab hours
with available tutors, and faculty office hours. We even encourage students
to work together with other students in the class to discuss how to solve
problems and help each other debug. (Please always type your own solution from
scratch, though, if you happen to be working with others.)  

There are many other people to help you and answer questions. However, it is
your responsibility to use those resources wisely, so that you and all your
classmates get the most out of them.

#### Try to figure it out yourself first
Remember that the point of the assignments are for you to learn, not to get
the right answer the easiest way possible. If you get stuck on something,
try working at it yourself for just a few minutes and see if you get anywhere.
Some students are quick to ask for help because it saves them time, and they
feel like they understand the solution when someone else shows it to them.
There is nothing wrong with this, but if all your hard problems are solved this
way, one of two things may happen. You might not be learning
things as well as you thought, and will find that when the supports are taken
away for the exam, you won't be able to perform as well as you did on the
homework and lab assignments. Or you may indeed be learning well, but
lack confidence because you haven't proven to yourself that you could have
gotten it on your own if you tried harder.

Whenever you run into a problem, try it yourself for a little while first, or
work with someone that also doesn't immediately get it yet.
If you solve it yourself, you will feel much more satisfied than you would
if you had someone else just explain it to you.

#### Don't waste your time by refusing help
On the other side, some people learn the previous lesson "too well", and think
that they have to figure out everything themselves to learn the most.
Remember back to the introduction to this section, when you are just starting
out, there are challenges that will likely be beyond your ability to solve at
first. If you try to solve a problem you're not at least on the cusp of
grasping yourself, you will spend a large amount of time on it for little to no
progress. Even if you do solve the problem eventually, chances are you won't
learn as much from it as you would hope, because the solution doesn't make
complete sense to you.

The people that refuse to get help often do learn well eventually, but I
believe that the learning process is shortened when you can have someone get
you unstuck. A good rule of thumb is that if you've spent a certain amount
of time on a problem, and feel like you haven't gotten anywhere, it will
probably take you that much time again to finally solve it yourself. Ask
yourself if it's worth it. In lab, 5-10 minutes of being stuck is usually
good enough to call in a ringer. On homework, maybe you spend 20-30 minutes
on a particular issue before going in to office hours or open lab.

#### Be respectful of everyone's time
Despite the large amount of support we have in this course, we can't
accommodate everybody doing their homework in office hours or open lab where
help is on call. The main reason we want people to start assignments early is
not because we expect it will take you forever, but because we want you to
have many opportunities to get stuck on your own, come to office hours or
open lab, and get yourself unstuck again. That's the mindset you should have
as you work on the homework assignments, because it will help use everyone's
time best.

You avoid wasting time, because if you ever get stuck and are about to waste a
bunch of time, you can just stop and shelve your work until the next open lab
or office hours. The instructors and tutors have their time used well, by
being able to spend the most time on the most important part - getting people
unstuck from the hardest problems. This lets us help more people, improving
the learning experience for everyone.

## Parting Words
Hopefully you found this guide helpful and encouraging. Whether or not you did,
remember that this guide is not intended to be a substitute for talking with
your instructor. If you have questions, concerns, or just want to tell us how
things are going in the class for you, our email accounts and office hours are
open for all those reasons in addition to immediate homework help. Even if
you just try out some of the suggestions here and found them helpful, I
personally would be glad to know.

We are your learning coaches, and are glad to work with you to make sure you
are learning as much and as efficiently as possible, and that you get a good
grade to show for it. This collection of advice is just one part of that,
and I hope you found it useful.
