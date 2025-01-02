# Experiences

## STAR method

- **Situation** - The interviewer wants you to present a recent challenge and situation which you found yourself in
- **Task** - What were you required to achieve? The interviewer will be looking to see what you were trying to achieve from the situation. Some performance development methods use "Target" rather than "Task". Job interview candidates who describe a "Target" they set themselves instead of an externally imposed "Task" emphasize their own intrinsic motivation to perform and to develop their performance
- **Action** - What did you do? The interviewer will be looking for information on what you did, why you did it, and what the alternatives were
- **Results** - What was the outcome of your actions? What did you achieve through your actions and what did you learn? What steps did you take to improve after the experience?

## STAR method experiences

| Omniscience Strategies | Fun Hackathon 2024 |
| ---------------------- | ------------------ |
| During the summer of 2024, I was a rising junior and did my first internship at Omniscience Strategies in California. It was a startup company, and I worked in a small team of three and my role covered tasks from vast domain including frontend, backend, infra, and DevOps. My team was developing a new llm web application. | In the summer of 2024, I was a rising junior and participated in my first hackathon at Hacker dojo. Hackathon was called Fun Hackathon 2024 and it was to create a project in two days in a team of 8 on the topic of startup ideas. I formed team with 5 strangers and started from idea generation, desiging, coding, and to doing presentation. |

| Situation | Task | Action | Results |
| --------- | ---- | ------ | ------- |
| In my part time job as web designer in college during the fall semester of my junior year, I worked on managing the college's photography website for storing and displaying images related to college's diversity. | As more images were added, the website became heavier and slower to load the photo, it was initially about 3 seconds but then it became about 10 seconds to load as we had about 100 images in the website. | To address this challenge, I first conducted a performance analysis to identify bottlenecks using inspect section from the browser. I found that browser spent much time on loading images that were not currently displayed on the screen. I introduced lazy loading on images, loading only the images that are on the screen currently. | As a result of the optimization, the loading time for the website decreased by 40%, leading to better user experience on the website. |
| Omniscience Strategies | Our goal was to create a demo version on schedule. | I collaborated closely with my team members, participating in daily stand-ups and code reviews. | Thanks to our teamwork, we successfully delivered the demo version on time, resulting in positive feedback from stakeholders. |
| Omniscience Strategies | Due to the small team size and product being in early stage, we did not have pipeline for testing and had to test manually, which slowed our development. | Rather than moving forward with this state, I decided to create a basic pipeline for testing. Implemented it by myself from scratch. | This boosted our development speed, covering 80% of the API endpoints. |
| Omniscience Strategies | At first, I had experience with frontend and backend through courses and personal projects, but not much experience on infra and DevOps. I had to learn many things including Terraform, AWS, Docker, infrastructure, and pipelines. | Of course I did some trial and errors during the work time, but also during my free time, I thought about the tech stack that I learned in the work and came up with ideas for personal projects to apply those tech stacks. Like twitter bot using docker and pipeline. | Through applying in my free time, I not only learned deeper on the subject but was also able to create something that I wouldn't had been able to create before. |
| Omniscience Strategies | One time, I was working on implementing chrome extension version of the product. When pulling firebase library, the extension gave an error message. Which was that Manifest v3, new version of extensions platform had different policy as v2 and did not allow pulling library from outside the code. It was migrated recently and did not have much documentation on the solution for this matter even on stack overflow or ChatGPT. | I spent hours doing research but could not find the exact solution for this but was able to figure out it was caused by the v3's new policy and that it does not allow pulling external library. So I decided to copy paste the whole source code for the library. | By copying the whole firebase library directly, I was able to solve the error. |
| Omniscience Strategies | It was my first internship and it was a startup with 3 members team, so I was tasked in vast area including frontend, backend, infra, and DevOPs. Also living in completely new area. | I did my best with every task and made sure that I complete them. | I was able to contribute heavily to my internship, also getting extended internship offer. |
| Fun Hackathon 2024 | We came up with the idea of making speech to text and then reformat text using llm. But we had conflicts in terms of what kind of output we want. One side was with creating structured like JSON file for API endpoints and the other side was creating analysis like summarization or todoList. I was with analysis but it took almost half a day just arguing. | To make the project forward, I adviced to let's code the common parts first and test each side to see which one is better. So the project moves forward. | We compared the result and voted that live analysis is better. And won 2nd place in the hackathon. Through comparing by product, we were able to compare them better than comparing in theory or words. |
| Fun Hackathon 2024 | We were strangers to each other and not all of us were able to code. | We split up the team so non-coders can work on coming up with ideas for how llm should be used with the text we get from the live audio. We used Git and React to make sure we work on different components to avoid conflicts and also split the presentation parts into parts that each of us were confident in. I took part in explaining tech stack. I also coded feeding live transcript to llm part. | We won 2nd place in the competition!! |

## past mistakes and improvement

1. Used terraform every time when testing script.
Test script directly inside the server

2. Ran pipeline every time when testing YAML script.
Test YAML script inside docker image.

3. Created branch that had too many unrelated changes.
Make each branch unique to only one purpose and rebase or reset if too robust.

4. Overengineered and added unnecessary feature to server.
To make project light, avoid adding unnecessary features.

5. Wrote a code that did not think about future. Automatically removing \n from logger.
Create removeNewLine function and use it when calling logger.

6. Tried to combine two db and messed up duplicated entries.
Make backup db before doing irreplaceable step.

## experience ideas

- Times when you felt a huge sense of accomplishment or success.
- Times when you fixed something that wasn’t working.
- A time when you had to make a challenging decision.
- A time when you had to influence a leader or team.
- Times when you got surprised by something or had overlooked something.
- Times when you removed barriers or came up with a creative solution.
- A time when you failed but learned.
- A time when you had to defuse​ an escalating situation.
