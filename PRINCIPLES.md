* Shared problems are solved faster
* Transparency forces authenticity and honesty
* Participative communities are more open to change
* Open standards provide business agility
* With more eyes, all typos are shallow
* [Jon Prall](http://jprall.typepad.com/blog/2010/10/85-operational-rules.html) - (2007) 85 Operations Rules to Live By
* Make decisions using the path of least regret
* The simplest explanation is always the most likely.
* [Christopher Diggins](http://www.artima.com/weblogs/viewpost.jsp?thread=331531) - The Principles of Good Programming
* You are the books you read, the films you watch, the music you listen to, the people you spend time with, the conversations you engage in. Choose wisely what you feed your mind.
* [Lars Kappert](https://webpro.github.io/programming-principles/) - Categorized Overview of Programming Principles
* [Lucas Medeiros Reis](https://dev.to/iamlucasmreis/the-single-most-important-driver-of-software-quality) - The Single Most Important Driver Of Software Quality
  * don't change code you don't understand
  * never merge a branch with known defects
  * use checklists to make sure the whole problem is solved
  * static analysis tools for everything
  * code review for everything
  * test (automated and manual)
  * make small changes and iterate
* [Ozan Onay](https://blog.bradfieldcs.com/you-are-not-google-84912cf44afb) - You Are Not Google
  * Don’t even start considering solutions until you **Understand** the problem. Your goal should be to “solve” the problem mostly within the problem domain, not the solution domain.
  * **eNumerate** multiple candidate solutions. Don’t just start prodding at your favorite!
  * Consider a candidate solution, then read the **Paper** if there is one.
  * Determine the **Historical context** in which the candidate solution was designed or developed.
  * Weigh **Advantages** against disadvantages. Determine what was de-prioritized to achieve what was prioritized.
  * **Think!** Soberly and humbly ponder how well this solution fits your problem. What fact would need to be different for you to change your mind? For instance, how much smaller would the data need to be before you’d elect not to use Hadoop?
* [Viktor Farcic](https://www.youtube.com/watch?v=mW_gkQnF4eU) - Jenkins World 2017: The Ten Commandments Of Continuous Delivery
  * every green commit is deployable
  * break silos : no departments, no silos. especially no CI/CD department
  * refactor 2-3 hours every day (to make your application deployable, testable, ...
  * educate others (the point is not for you to make the work / build pipelines for others) but others need to learn and do it 
  * be small : split monoliths (otherwise they take a long time to test / refactor / build / need big teams etc)
  * practice TDD. no tests, no commits
  * define your CD pipeline as code (no more clicking around)
  * have a fast pipeline (fast feedback is important, in minutes or at best one coffee, no longer !)
  * priority highest on fixing failed pipelines : never start ignoring failures. there is nothing more important in the world but fixing a failed build. If you don't fix it now it will cost much more.
  * fix it first, drive later
  * don't use sonar rules : either your build is ok or isn't, you cannot play with % to decide if your build is ok.
  * you should your CD pipeline locally : you should not wait for jenkins to do everything. test first locally, then commit and have jenkins do the final verification but commiting code you didn't test locally should be illegal
  * commiting code you didn't test locally should be illegal
  * respect your coworkers
  * continuous integration is about committing only to master branch : working on different branches means you don't trust your process. Ff you trust your process you know that the pipeline will detect problems. working on different branches only delays the detection of problems (verification, integration with everybody's else code). If you really like branches, make short lived feature branches (max 1 day) then merge them back to master and deploy to production
* do pull requests
* prioritize
* finish what you're doing, focus on a small number of tasks in parallel. 

# from my Bullet Journal
## Values 
* Learn the basics of a language before learning frameworks
* DRY (Don't Repeat Yourself) is not about code, but about knowledge
* Refactoring is a development technique, not a project
* Break rules, take risks.
* True leaders want everybody to be great.
* True leaders don't respect discipline.
* Build and grown trust otherwise it can't work
* Best way to convince is by giving an example / by showing it exists
* Everything we do expresses a need
* We often eat only what we already like / know
* We all criticize, we need to be aware of it
* Violence is an answer to unsatisfied needs
* Take pleasure in simple things
* Ban negative thoughts
* Take the time you need, don't go too fast
* Take risks 
* Ask for help when struggling
* Don't do to others what you don't want done to you
* Write down your ideas and your Aha moments
* Share your feelings, don't hide your humanity 
* Don't let other people decide your future for you
* Give your word. 
* Say no rather than "I don't know" or "whatever you wish"
* Doing / saying nothing is already telling something
* Let go of control / release the need to control
* The faster you do a task the more you learn and the sooner you become satisfied
* The slower you do a task the more painful it will be
* Say thanks
* Smile
* Give, share
* Take time for you, for important things and people
* Keep in touch, maintain friendship
* Market yourself. You're putting on the effort, make sure you show it
* Go right to the point
* Ask why
* Keep your ability to be amazed by things and people, they won't last forever
* Act to fight perfectionism
* Take advantage of any opportunities that present themselves
* Physical and visual contact rather than emails, sms, chat
* Accept people as they are
* Select your friends
* More slow, minder stress
* Remain calm and quiet about everything which you will experience
* Reinvent yourself, evolve
* Grow and progress in love, work, leisure
* Be yourself, know yourself
* Be curious, observe and play (mentally, physically) with what surrounds you
* Be positive
* Be realistic, concrete
* Understand your goals and others' goals
* Taking notes, writing things down is a way to free your mind and not forget or lose anything. It's also a way to train your senses of observation and reflection
* Observe without judging, relate facts
* Choose the right tool for the job
* Don't multitask
* Achieve what you're doing before you move to something else
* Life doesn't get easier you just get stronger
* living isn't fucking easy but at least you can make your life more fun
* when you pause what you're doing, you find more interesting ways to do it. So pause often
* Be you ! the world will adjust

## Art of Questions
* Just ask
* Explain your misunderstanding 
* Explain / state what you know / don't know
* Sound confident
* Have a come back
* Know first which answer type you're expecting : Opinion ? Factually correct answer ? Well reasoned judgment ? 
* Avoid "yes" or "no" questions 
* Dig deeper (5 Why...)
* Use the power of silence
* Don't interrupt
* Prepare the topic (know a bit what you are talking about)
* Check your assumptions (are you sure about what you think you know ?)
* Find the right person to ask
* Use correct grammar
* Keep the question simple
* Differenciate between open (Why ?) vs closed (when ? who ?) question types
* Explain why you are asking 

## Art of Communication
* Never use "never", always avoid "always"
* Suggest, don't criticize
* Don't make important decisions alone
* Don't cut communication, don't go away, don't flee
* Share your needs, your wills, your tastes / opinions
* Mutually listen to each other. Know how to listen. Use your right ear for listening (right ear = left brain) 
* Feedback is important : Show interest (nod, smile, ...)
* Talk about the connection you have with the other person
* When you communicate a hard decision, don't hide behind emails, talk directly to your audience
* Use the [SBI tool](https://www.mindtools.com/pages/article/situation-behavior-impact-feedback.htm) (Situation - Behavior - Impact)
* Assertiveness is ability to say yes to the person, no to the task 
* Respond rather than react
* Prepare, verify carefully what you will communicate
* Check if your message has been heard and understood
* Expect / Give feedback 
* Know the 7 C's : Clear Concise Concrete Correct Coherent Complete Courteous 
* Set the main idea first
* Focus on your audience
* Avoid passive constructions
* Be open minded, don't think you know eveything about your audience
* Use the body language (physical and visual contact, ...)
* Stay calm : Wrap up then stop talking. Pause. Repeat. Ask clarification of a statement. Be clear. 
* Look for humor. 
* Look for compromise if the other cares about something not important for you 
* Agree to disagree : take beak so everyone calms down 
* Assert yourself : express (negative) opinions and needs positively. Ask for help. Learn from errors. Accept feedback. Say no
* Observe rather than interpret. Communicate facts not interpretations
* Understand people's needs/feelings
* Use non violent communication 
