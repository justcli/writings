Over the last decade, automated testing has undergone major changes. Its adoption has increased. And so has its very nature. These days, automated tests involve code writing. Testers use java, javascript, ruby, and other languages to write their test codes. So much so that a tester with little or no knowledge of these languages would not be considered a real tester.

What I am going to argue is completely against this trend. Here I propose some reasons why testers should not code.

## Programmer’s Curse

Like testing, coding comes with its own set of nuances. One of these is what I call the programmer’s curse. Whenever a programmer writes code, he leaves bugs in the code. In short, code always comes with its quota of bugs. We can not have a bug-free code (almost). And this is true even for experienced programmers. So, what do you think are the chances that a tester (otherwise a rookie programmer) could produce a bug-free code? You might say that a tester does not write lots of code. For every test scenario, he writes a few lines of code. But that does not change much. All it takes is a typo to turn a code on its head. And that is just the start of the worry. Once the tester writes code, expect him to go thru the same mess that every programmer goes thru. Do not pretend that he is exempted from it all as a tester. One can not become a good tester by being a poor programmer.

In short, you can not escape the programmer’s curse while programming.

## Tester’s Own Turf

A tester, like any artist, must always try to keep improving. In the real world, it means enhancing his test skill and judgement. You read it right. One can not become a good tester without judgement. It is the judgement that makes testing an art at some level. To achieve it, a tester must always focus on the core of testing and avoid the periphery. And by any measure, coding is not part of the core. That doesn’t mean a tester should not know to code. Every tester must know one scripting language. But there is a difference between programming and scripting. You could read more about it here. In any case, a tester must invest his time into the art of testing, not learning new programming languages.

A tester should master his own turf than venturing into another.

## Inefficiency

As programming is creeping into the testing world, companies are investing more time and money into hiring and training testers. This is a hidden cost that does not pay itself back. In fact, if we go with the past experiences, it ends up being a burden for the company as well as the testers. This is a very inefficient use of resources.

The inefficiency is visible even at the tactical level. The coding frenzy among testers has given us some inefficient and horrible pieces of code. Every commonsense of programming practice has been done away with. With such a riot going on, it is easy to find how inefficient test codes generally are. Look at any BDD test code (aka Cucumber step file) and you will see mutilated pieces of code scattered around with function names hanging on their heads.

Common sense is not so common.

## Automation ≠ Programming

The invasion of programming in the testing world is driven by automation. In fact, automation and programming are inseparable today. But that is far from reality. Automation has little to do with programming. In fact, we can do all test automation with nothing more than scripting. If you need one, the better half of automation would be CLI. CLI goes well with test automation. I must clarify that any unit level testing should not be part of the automation process.

I do concede that the test automation world lacks tools that allow automation using only CLI. If I want to switch from rest-assured to a CLI tool, I do not have many reliable alternatives. But that is not the reason for the invasion of programming in the testing world. The reason is that testers, as a community, never challenged the notion of tester-as-a-rookie-programmer.  The testers must resist the urge to showcase our programming naivety as our programming skills. There is something I call tester’s pride.

Be proud of your testing acumen, not your programming naivety.
