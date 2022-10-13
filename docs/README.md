# BDD - Kata - Nimmt6

For this kata, participant are asked to implement the rules of a card game: [Nimmt6](https://en.wikipedia.org/wiki/6_nimmt!).
The rules of this game are quite simple, but will it be easy to implement them? 

Since the rules are well established, it is a good idea to start your development using BDD and TDD to validate your progress
and, the most important, to gain some practice on this development method that are often neglected.

## 3 levels

### Let's get straight to the code

Setting up a project for BDD and writing the feature files can be cumbersome. So 2 repos have been created to help you:
* a first one containing a base maven project (for now only in [java](https://github.com/kata-XDD/base-java-8) 
  and [kotlin](https://github.com/kata-XDD/base-kotlin))
* a [second one](https://github.com/kata-XDD/nimmt6-features) containing a basic set of feature file that describe 
  some rules (not all) using the gherkins language

### Feature files at heart

Only the setup of the project is done (so you don't have to spend to much time in configuration).

You will have to write the feature files yourself since this is also a really good exercise (in real life, you most probably won't
have those file ready for you and you will have to write them along the evolution of your projects).

### Look ma, no hands !

Creating and configuring a project, writing its specs and implementing them are, *in fine*, all developers' tasks.
So you can give it a try and start it from scratch.

## Tips and advices

1. base repo are provided, but they are not the only possible setup or feature possible. If there is something
   you don't like in it, you are free to change them. As long as you practice BDD and TDD, you are on the right track.
2. No deliverable is expected. Once again, this is for you to practice.
3. The choice of implementation is free, but if you don't know where to start, I could suggest to see the final
   code as a library that validate those rules.
4. Do it in as a team exercise and share you progress on regular basis and discuss your ideas and approaches. BDD and TDD
   alone won't make a good dev out of you. Sharing will. It will help you by:
   - either learning some things
   - practicing how to argument your design and implementation choices
   - sharing your frustration and how you emotionally tackled the task

## Resources

For the kata
- [kotlin base project](https://github.com/kata-XDD/base-kotlin)
- [java base project](https://github.com/kata-XDD/base-java-8)
- [some feature files](https://github.com/kata-XDD/nimmt6-features)

Other useful resources:
- [Cucumber's takes on BDD](https://cucumber.io/docs/bdd/)
- [writing good feature files](https://automationpanda.com/2017/01/30/bdd-101-writing-good-gherkin/)
- [Cucumber's blog on BDD and TDD](https://cucumber.io/blog/bdd/bdd-vs-tdd/)