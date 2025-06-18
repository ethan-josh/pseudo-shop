# Final Project Retrospective

## Team Members
- Student 1: Adrian Garett Sian
- Student 2: Ethan Joshua Camingao

## 1. How did you divide the work between you and your partner?
_(Who worked on which features? How was the work assigned or negotiated?)_

**Garett**: We divided the work into two parts. Ethan was assigned to do the login and filtering of product while I was assigned to do the product creation and displaying of products. 
The work was assigned on which we prefer comfortable doing in this part of the project.

**Ethan**: We divided the work on the features equally amongst ourselves. I was in-charge of the `feat/user-registration` and `feat/filter-by-product-attributes`.

## 2. What Git strategies or commands helped you most during the project?
_(E.g., branching, rebasing, frequent commits, etc.)_

**Garett**: The commands that I used most frequently are 'add' and 'commit'. I use these often because each commit represents a new feature. I avoid compiling all the changes into a single commit because it is more difficult to identify and revert specific errors when they are grouped together in one large commit. I also use the 'pull --no-rebase' command, as it is the proper way to pull changes from GitHub and it clearly shows any merge conflicts. Lastly, the command I use the least is 'push'. I usually compile all the commits and push them only after I am done coding.

**Ethan**: For me, I found the branching command particularly useful especially in working asynchronously. In addition to this, using `git log`, `git diff`, and `git status` to remind of the updates I have made and what I am committing in order to avoid errors.

## 3. Describe a merge conflict you encountered. What caused it and how did you resolve it?
_(Include any lessons learned or techniques used to resolve the issue.)_

**Garett**: We encountered a merge conflict in the product_model file. Ethan named the variable product_List, while I named it item_list. When I requested a PR, GitHub reported the conflict. We decided to keep the original name, product_list, as it aligns better with the file name, product_model.

**Ethan**: It was actually difficult for us to create a conflict. Given that our communication lines were quite open and we were able to plan ahead of time, we didn't encounter any conflicts with our given task. In order to simulate the conflict, we had multiple trial and erros just to create a merge conflict. This actually allowed us to be reminded of what causes conflicts in the first place. In order to resolve our generated merge conflict, we had the partner review the conflict.

## 4. What were the biggest challenges you faced as a team?
_(This can include communication, Git usage, or coordination.)_

**Garett**: The biggest challenge we faced as a pair was causing a merge conflict. Since we were synchronized in the tasks given, we did not encounter a merge conflict initially. The conflict happened after we attempted to figure out the product_model file and brainstormed ways to improve the variable names in that file.

**Ethan**: Mentioning my answer in number 3, one of the challenges we faced as a team was actually simulating the merge conflict. Ironically, we found ourselves communicating via a live-call just to simulate a merge conflict while the rest of the feature work was done just through messaging lines.

## 5. What did you learn about using Git in a collaborative setting?
_(Any insights or habits you’d apply in future projects?)_

**Garett**: I learned that using Git in a collaborative setting requires not just technical knowledge, but also communication and coordination. Branching and pull requests help keep individual work separate while allowing for smooth integration. I also realized how important it is to write clear commit messages, resolve merge conflicts carefully, and follow a shared workflow. Most importantly, Git makes teamwork more efficient and traceable, especially when everyone aligns on best practices.

**Ethan**: Git is a powerful tool that allows for collaboration between multiple teams or individuals. One habit that I learned from this exercise is the need to communicate task and assignments well initially. With an initial understanding of what a person is supposed to do, this is will prevent unnecessary complications down the line. To add to that, I would also like to apply the PR feature of Github in the future to let other team members check my work.

## 6. How would you improve your workflow next time?
_(Think about technical habits and teamwork practices.)_

**Garett**: Next time, I would improve my workflow by setting up clearer task breakdowns including the names of the functions early on and aligning better with the team on priorities that needs to be finished. I’ve realized the value of consistently using tools like Git issues, branches, and pull requests with proper labels and documentation. I’d also allocate more time for code reviews and automated testing to catch issues earlier.

**Ethan**: Open communication lines is a must-have. Preferrably having daily standups or meetings should keep everyone aligned.

## 7. Optional: Any feedback on the activity?
_(What worked well? What was confusing or could be improved?)_

**Garett**: The activity was well-structured and gave a clear understanding of how product features are broken down and translated into pseudo-code. It helped reinforce key concepts like modular design, separation of concerns, and collaborative coding practices. In terms of Git and GitHub, the collaborative aspect taught me how important it is to follow consistent workflows—like branching strategies, writing clear commit messages, and managing pull requests. I also appreciated the exposure to resolving merge conflicts and reviewing code changes, which are critical skills in real-world development.

**Ethan**: This activity was able to simulate well the workflow of two different individuals in a git setting. I think it could be improved to cater to larger team collaborations. Maybe have 4 members in one team and with each working on interdependent features.
