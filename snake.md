---
title: "Orchestrating 15 People to Build Snake"
permalink: /snake
---

# Orchestrating 15 People to Build Snake
For a university software project we were assigned the task to build the calssical snake game in our exercise group. An MVP should be ready in two months and there are no requirements. So I'm here to document it all.
It sounds like an easy task, in fact, to get a glimpse of the game engine LibGDX that the team decided upon, I just built snake in an hour. So we're finished, aren't we? My plan is to use this project to simulate a 
real team. It's a green field for testing out group structure, communication processes, building engineering culture and finding the right architecture.

## The Team
We are about 15 people, of whom 7 want to be developers and 7 designers. I will be the requirements engineer and try to manage the team as well as I can. The students mostly have no real experience on projects, only 4 have, 
so communication about why we decide to do things in a specific way, like choosing the MVC-Architecture rather than not choosing it, is key to not leave anyone behind. It is a really small project for too many people.

## The Process
So we were introduced to scrum in the lecture and immediately thought about how we can apply it to our team. But we quickly realized that our team is too big for scrum. Facilitating everyone to take part in the weeklies is 
too much effort. At first i had the idea to split the team into two scrum teams and managing them mostly seperately by also splitting up the Game into disjunct parts like dev/design, kind of like a scrum of scrums. 
We decided to go with a simpler method: Kanban. 
As long as the *requirements are formulated understandably, concisely and are precise enough, everyone should be able to just pick a task and go with it*. But this poses another challenge. How do we reduce coupling of the tasks, such
that everyone can work asynchronously without waiting for everyone else to finish the tasks that they depend on. So we have to be cautious when defining the requirements and turning them into a task, so that, optimally, we write 
the tasks in such a way, that they are decoupled, or that we have at least enough decoupled tasks for everybody, which is more realistic. To make it even more realistic, I will try to propose paired working, such that we only need
4 decoupled tasks per team per week and we have less quality risks. This is also a realistic workload for students. So how do we archieve *loose coupling* between features and teams?

## The Architecture
*This is what has the biggest influence on the productivity of our team*, which i measure heuristically by potential waiting time for new tasks. First of all: separation of concerns. Using the MVC-approach the graphics team
can work on the view, while the dev team can work on the controller. Let's see if we can get this to work with our only communication slot available, which is once per week 45 min after the exercise. Also this approach enables us
to add more features later more easily. 

## My Task
- formulate requirements after best practices
- keep track of requirement dependencies and manage them accordingly
- facilitate productive weeklies
  - for example in the first week we were still in the forming phase of our group and I created a collaborative doc to collect points for our agenda
  - I'm not a good moderator yet, so we have another guy who can do it, I trust him in that
- overseeing team structure
- gather feedback on the progress to adapt the tasks and keep track of the progress for us to meet the deadlines
- be active in influencing the architecture for a good flow of our project
