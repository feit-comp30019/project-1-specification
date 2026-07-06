# Project 1: Game Design and Prototype
**Participants:** This project is to be completed in groups of 3-4 people.

**Marks:** This project counts towards 40% of your marks for this subject.

**Due date:** Multiple submissions required; see the [schedule](#schedule) below.

## Schedule

This project is split into several milestones, each with its own deadline.
Milestones 1, 2 and 3 are team submissions, while Milestones 4 and 5 are
submitted by each team member individually. All group members are expected to
partake fully in all team milestones.

#### Team submissions

- [Milestone 1 | Team Declaration](#milestone-1-team-declaration) ... due **Sunday 16 August, 11.59 pm Melbourne time**
- [Milestone 2 | Game Design Document](#milestone-2-game-design-document) ... due **Sunday 3 September, 11.59 pm Melbourne time**
- [Milestone 3 | Unity Prototype](#milestone-3-unity-prototype) ... due **Sunday 10 September, 11.59 pm Melbourne time**

#### Individual submissions

- [Milestone 4 | Team Member Evaluation](#milestone-4-team-member-evaluation) ... due **Wednesday 21 September, 11.59 pm Melbourne time**

## Table of Contents
- [Assignment Brief](#assignment-brief)
  - [Overview](#overview)
  - [Requirements](#requirements)
  - [Development Tools](#development-tools)
- [Milestone 1: Team Declaration](#milestone-1-team-declaration)
- [Milestone 2: Game Design Document](#milestone-2-game-design-document)
    - [Game Overview](#game-overview)
    - [Story and Narrative](#story-and-narrative)
    - [Gameplay and Mechanics](#gameplay-and-mechanics)
    - [Levels and World Design](#levels-and-world-design)
    - [Art and Audio](#art-and-audio)
    - [User Interface (UI)](#user-interface-ui)
    - [Technology and Tools](#technology-and-tools)
    - [Team Communication, Timelines and Task Assignment](#team-communication-timelines-and-task-assignment)
    - [Possible Challenges](#possible-challenges)
  - [Submission](#submission)
- [Milestone 3: Unity Prototype](#milestone-3-unity-prototype)
  - [Submission](#submission-1)
- [Milestone 4: Team Member Evaluation](#milestone-4-team-member-evaluation)
- [Assessment](#assessment)
- [WebGL Builds](#webgl-builds)
- [Gradescope Submissions](#gradescope-submissions)
- [Late Submission Policy](#late-submission-policy)
- [Academic Honesty](#academic-honesty)
  - [Unity Asset Store](#unity-asset-store)
  - [Credit where credit is due ...](#credit-where-credit-is-due-)
- [Resources and Help](#resources-and-help)


## Assignment Brief

### Overview

**The theme:** *Sci-fi Worlds*

You are tasked with designing a sci-fi game. Your creation should transport players to a world shaped by advanced technology, the unknown reaches of space, or visions of the future. You should strive to challenge conventional gameplay mechanics by incorporating creative elements that make your world feel genuinely alien or futuristic. Some examples of games that fit this theme you could take inspiration from include (but are not limited to):

  - No Man's Sky
  - Dead Space
  - Cyberpunk 2077
  - Bioshock
  - Mass Effect
  - Subnautica
  - Doom
  - Titan Fall
  - Death Stranding
  - Fallout
  - Portal
  - Space Engineers
  - Deep Rock Galactic
    
In this first project, your team will focus on the conceptual design and
initial prototype of your game. You'll come up with an initial concept, design
the basic mechanics, and the art style, and implement a prototype in Unity. This
part of the assignment allows you to experiment and refine your game concept
before heading into the more technical development phase in Project 2.

### Requirements

Although the premise, art style and mechanics of your game are up to your team
and creativity is strongly encouraged, there are some high level requirements
that must be adhered to:

- The game must be designed to address the _Sci-fi worlds_ theme as described
  previously.
- The game must be _single-player_ and simple enough in scope to be completed
  by the end of the semester. No more than 10 minutes of gameplay should be
  required to complete the game.
- The game must be designed to be played in a computer web browser (as a WebGL
  build).
- The game must be developed using [Unity 6.3 LTS](https://unity.com/releases/editor/whats-new/6000.3.18f1#notes) and tracked on GitHub (see
  [Development Tools](#development-tools) below).

Both projects in this subject must be completed in the **same** group of 3-4
people. You can choose your own team members, but **you must have a team by the
first milestone deadline.** Please attend lectures and workshops in the first
couple of weeks to meet others looking for group members, if you don't already
know others in the subject. 

Developing even a simple game is very challenging and time-consuming, so it's
important to develop a clear vision and a solid plan as a team. You'll need to
work together to ensure that everyone's ideas are heard and that the workload
is distributed fairly _from the start_. We strongly recommend that you seek out
team members who share similar ambitions and work ethics.

> [!IMPORTANT]
> All team members are expected to contribute equally, and you'll be asked to
> evaluate your team members at the end of both projects in this subject. See
> the [Team Member Evaluation](#milestone-4-team-member-evaluation) milestone
> for more details.

Before commencing work on the project, everyone in the team is expected to read
this specification document in full, including the [Assessment](#assessment)
section which provides details on our full set of expectations for this project
and how it will be marked.

### Development Tools

You'll be collaborating with your team via GitHub. The first workshop
of the semester (week 1) covers the basics of Git and Github, so
ensure that you've completed it in full before starting work on the project.

Your prototype ([milestone 3](#milestone-3-unity-prototype)) must be developed
with [Unity 6.3 LTS](https://unity.com/releases/editor/whats-new/6000.3.18f1#notes), using the template
provided in your team's repository as a starting point. A `.gitignore` is also
already included in the repository. All team members are expected to regularly
commit and push their contributions to GitHub. Note that the git commit history
may be used as evidence when considering individual contributions to the
project (i.e. in the event of a dispute).

> [!TIP] 
> Before beginning work on the project you should discuss strategies as a team
> for avoiding and resolving merge conflicts, as these can be a major source of
> frustration and wasted time.

## Milestone 1: Team Declaration
**Due: Sunday 16 August, 11.59 pm Melbourne time (team submission)**

After you have formed a team of 3-4 people, set up an initial meeting and
complete the following steps together:
1. Come up with a **team name** and designate a **team leader**. The team
   leader is responsible for setting up the team on GitHub and submitting the
   project on each milestone deadline. We recommend that you choose a team
   leader who is comfortable with Git and GitHub. 
   
   To ensure compatibility with our grading systems, please only pick a team
   name that is alphanumeric characters, spaces, underscores and/or hyphens (no
   other special characters). Names should also be between 3 and 50 characters
   in length.
2. On behalf of the team, the **team leader** should create a single 
   `metadata.json` file following the format below.

    ```json
    {
      "teamName": "Your Team Name",
      "teamMembers": [
        {
          "name": "Team Leader Name",
          "github": "leader-github-username",
          "email": "<leader_email>@student.unimelb.edu.au"
        },
        {
          "name": "Second Team Member Name",
          "github": "second-github-username",
          "email": "<second_member_email>@student.unimelb.edu.au"
        },
        {
          "name": "Third Team Member Name",
          "github": "third-github-username",
          "email": "<third_member_email>@student.unimelb.edu.au"
        }
      ]
    }
    ```

   If your team has four members, you should add a fourth object to the
   `teamMembers` array.  
3. Submit the single `metadata.json` file to Gradescope as per the instructions under
   the [Gradescope Submissions](#gradescope-submissions) section below. To
   launch Gradescope and connect it to Canvas for the first time, click on the
   big button at the end of the <a
   href="https://canvas.lms.unimelb.edu.au/courses/239872/assignments/659411">Milestone
   1 LMS page</a>.
4. Once the submission is complete and the validation tests pass, a repository will be created
   on your behalf and your entire team will be granted push access to this repository. 
   **Your repository URL will be shown in the Gradescope output**.
   A single commit will be automatically pushed to the repository containing a template
   `README.md`, `REPORT.md` and a bare bones Unity project. This is the starting point for
   your team's game design document and prototype. Please ensure that **all team
   members** can **pull and build** the project for WebGL locally. If successful, you
  will see a simple Unity scene with a cube at the origin.
5. To test your push access in the repository, please **commit and push** the same `metadata.json` that you 
   submitted to gradescope to the top level of your repository. **All team members** should pull the changes from GitHub 
   to ensure that they.

In subsequent milestones, the Unity project in the repository will be
automatically built and deployed to GitHub pages whenever you submit your
project on Gradescope. This allows you to play the latest version of your game
in a web browser, and is a key part of the assessment process.

> [!WARNING] 
> For all milestone deadlines, including this one, **every team member** (not
> just the team leader) is expected to verify that they can see the submission
> on Gradescope, and that all validation test cases pass. Test cases may differ
> between milestones. If you're having issues, please contact the teaching team
> via a private post on the discussion board.

## Milestone 2: Game Design Document
**Due: Sunday 6 September, 11.59 pm Melbourne time (team submission)**

> [!CAUTION] 
> Ensure that you have successfully submitted the first milestone via
> Gradescope before starting work on this one. Important template files will
> not be available in your team's repository until all validation tests pass
> for the first time. Continuing without these files will lead to significant
> issues later on.

By this milestone, your team must have **drafted** a Game Design Document (GDD)
in the repository's `README.md` file. The GDD should provide a detailed vision
of your game, allowing any member of your team (and the teaching team!) to
understand exactly what your game will be. **We are expecting this to be a very
visual document**. You should use illustrations, sketches, photos, gifs, etc.,
liberally throughout the document.

> [!NOTE] 
> The GDD is intended to be a "living document", meaning that it will be
> updated as your game evolves. You should have a final draft of the GDD ready
> by this milestone, and be ready to start prototyping (as per the third
> milestone). Ensure that you keep the GDD up-to-date as you make changes to
> your game, so that it always reflects the current state.

Below is a suggested structure for your GDD. You are welcome to adapt it as
needed to best convey your team's vision, but either way, ensure that you
comprehensively cover all relevant points outlined below. Make sure that it is
clear how the overarching [theme](#overview) is integrated into the various
facets of your design.

#### Game Overview
Here you should provide a concise summary of your game and explain why it is
interesting, relevant and unique. Try to capture the essence of your game in a
concise manner and make the reader excited to play it. Questions to consider
include:

  - **Core Concept:** What is the core concept of your game? What is the main
    idea behind your game? Who or what is the "player", and what is their role
    in the game?
  - **Related genre(s):** What genre, cross-genre and/or sub-genre does your
    game fall into? What are some other games that are similar to yours? What
    makes your game different from these other games? 
  - **Target Audience:** Who is your game aimed at? Is there any demographic
    you are targeting in particular? Note that later this semester you will be
    required to conduct user testing with your target audience, so it should be
    feasible to recruit participants for this purpose.
  - **Unique Selling Points (USPs):** What makes your game unique? What are
    some of the key features that will make your game stand out from others in
    the same genre?

#### **Story and Narrative** 

If your game includes a narrative or characters aside from the main character,
describe them here. Discuss the plot, character backgrounds, and how the story
will unfold as the player progresses in the game. (If your game is not
narrative-driven, some of the questions in this section might not be relevant.)

- **Backstory:** What is the backstory of the game? What is the setting? What
  is the main conflict? If there is a story, how does it unfold as the player
  progresses through the game? 
- **Characters:** Is the player the only character? Is there a villain or boss?
  Who are the main characters in the game? What are their backgrounds? What are
  their motivations? What are their relationships with each other? What are their
  goals? What are their personalities? What do they look like?


#### **Gameplay and Mechanics** 

This is where you describe how the game works from the player's perspective.
Detail the actions the player can take, challenges they will face, and rewards
they can earn. The reader should be able to understand how the game progresses
over time, and what makes it fun to play.

- **Player Perspective:** Describe the player's perspective in the game. Is it
  first-person, third-person, or something else? Is the camera fixed or can it
  be moved? Is the player character visible on screen? If so, what does it look
  like? 
- **Controls:** Describe the controls for the game. What buttons or keys does
  the player need to press to play the game? Are there any special controls or
  combinations of controls? How does the player interact with the game world?
- **Progression:** How does the game progress over time, and what challenges
  does the player face? How does the difficulty increase over time? How does
  the player "die" or "lose" the game? Is there a scoring system? What makes
  the player want to keep playing? 
- **Gameplay Mechanics:** What gameplay mechanics are used in the game? What
  actions can the player take? What rules or "laws" govern the game world? What
  are the core mechanics that make the game fun? How do these mechanics fit in
  with the overarching theme?


#### **Levels and World Design**

Describe the game world and layout of the game’s level(s), including any
necessary sketches or diagrams. Include what the player will see, how they will
navigate through the game world, and what they will interact with.

- **Game World:** Describe the game world, and how it is captured on-screen. Is
  it 2D (see warning note below), 2.5D or 3D? Is it a single screen or does it
  scroll? Are there multiple levels? How does the player navigate through the
  game world? Is there a map or minimap?
- **Objects:** What objects are in the game world? What do they look like? What
  are their roles? How do they interact with the player? How do they interact
  with each other?
- **Physics:** What physics are present in the game? How do objects move? How
  do objects interact with each other?

> [!WARNING] 
> It's best to avoid developing a true "pixel-perfect" 2D game unless you are
> up for an extra challenge in Project 2. There will be less flexibility when
> it comes to the choice of shader techniques (you haven't learned much about
> shaders yet, so it will be hard to comprehend the implications at this
> point). A safe middle ground is to restrict the gameplay to two axes, but
> still render a 3D environment. This is sometimes called "2.5D".

#### **Art and Audio**

Convey the overall artistic style of your game, key visual elements, as well as
any other sensory or "artistic" elements such as sound and music. 

- **Art Style:** What is the art style of the game? What does the game look
  like? What are the colours, shapes, and textures used? What is the overall
  aesthetic? Concept art and/or references to games with similar art styles
  might be helpful here.
- **Sound and Music:** What is the sound design of the game? What sounds are
  used? What music is used? How do the sounds and music fit in with the overall
  aesthetic and themes of the game? 
- **Assets:** What "artistic" assets are going to be used in the game? How are
  you planning to create or source these assets? Provide a list of candidate
  assets (e.g., URLs) and their sources if you are sourcing them from the
  internet.

> [!NOTE]
> Remember that your game will be played in a web browser (as a WebGL build),
> and there may be technical limitations arising from this. It's preferable to
> aim for a simple but consistent aesthetic over "AAA" game graphics that might
> not be feasible to deploy in this environment. Prototyping and testing during
> milestone 3 can help you determine what is feasible and what is not.

#### User Interface (UI) 

Describe the game's UI, including things like health bars, score displays, and
menu screens. Detail both the functionality and aesthetic design of the UI.
Include any diagrams, wireframes or sketches to assist with visualisation.
Ensure that the UI design is consistent with the game's overall aesthetic.

#### Technology and Tools 

List the software and tools you'll be using to create the game. Justify your
choices as needed, and include any relevant version numbers or links. Of
course, you must use Unity and GitHub as per the requirements of this project,
but you may optionally include other tools such as image editing software,
audio editing software, or 3D modelling software (you aren't expected to learn
how to use such tools from scratch, but you can use them if you already know
how).

#### Team Communication, Timelines and Task Assignment

Provide a detailed plan of how you'll distribute the work amongst your team,
and what communication channels will be utilised to facilitate discussions. You
may wish to use a project management tool such as
[Monday.com](https://monday.com) or [Trello](https://trello.com/) to help you
delegate tasks and track your team's overall progress. 

> [!IMPORTANT]
> It is an expectation that your team communicates in English for all
> project-related activities. This is important to ensure everyone is included
> equally, and also so that the teaching team can understand your discussions
> in the (hopefully unlikely) event that we need to intervene.

#### Possible Challenges 

Discuss any potential difficulties you foresee during the development of your
game, and how your team plans to address these issues as they arise. These
could be technical challenges, time constraints, or anything else that might
impact your team's ability to complete the project. Prototyping and testing can
be particularly helpful here, and you should trial these out in the next
milestone.

### Submission

Once you've completed the final draft of your GDD, remember to commit and push
all changes to GitHub, resolve any merge conflicts, and once again ensure that
all team members can see the "final draft" on their local machines. Finally, as
a team, submit the project repository on Gradescope as per the instructions
under the [Gradescope Submissions](#gradescope-submissions) section below, like
you did for the first milestone.

## Milestone 3: Unity Prototype
**Due: Sunday 13 September, 11.59 pm Melbourne time (team submission)**

For the third and final team milestone in this project, you will create a Unity
prototype that serves as a "proof-of-concept" of your game, reflecting the core
mechanics outlined in the GDD. The goal of this task is to build a solid
foundation to expand on in the next project, where you'll be developing the
game in its entirety and evaluating it with end users. 

Your team should use the prototype as a means to prove that the game outlined
in your GDD is feasible to implement by the end of the semester, both technically
and in terms of scope. Don't worry too much about making things "polished" or
"pretty" at this stage, and we aren't expecting a fully functional game.
That'll come later!

> [!IMPORTANT]
> In the template project provided, there is a scene called `StartScene` which
> is expected be to be the entry point to your prototype. You can add
> additional scenes if needed, but ensure that the `StartScene` is the one that
> gets everything started.

In order to secure a good mark for this milestone, your prototype should meet
the following criteria:

- It should be possible to control the player character(s) and interact with
  any other characters described in the GDD (including any animations that
  support their actions). The game world should be sufficiently developed to
  facilitate these characters and control mechanics, but it's acceptable if the
  world is "small" or not fully fleshed out at this stage.
- Camera mechanics as described in the GDD should be operational. You should
  showcase your proposed camera perspective, and how it interacts with the
  environment, the characters, and any special camera movements.
- Externally sourced (artistic) assets that you plan to use in the final game
  should be showcased. They don't all have to be "functional", but it should be
  evident that they will be compatible with the game's art style, while _also_
  being technically feasible in a WebGL deployment (particularly with respect
  to performance and file size).
- The prototype must be consistent with the GDD, and provide a solid foundation
  for further development into a complete, fun and polished game. It should be
  clear that the vision outlined in the GDD is feasible to implement by the end
  of the semester.

> [!WARNING]
> The `Assets` folder should be kept organised, and **must not exceed 250MB**.
> The game should run at a reasonable framerate (30fps or higher) on a typical
> laptop computer web browser. Remember to regularly build and test your Unity
> project as outlined in the [WebGL Builds](#webgl-builds) section below. 

It is okay to reduce the scope of your game if you discover that it is too
ambitious as a result of your prototyping, just remember to update the GDD
accordingly. Identifying and addressing unforeseen issues now will help you
avoid problems later on, and is in fact a key part of the design process. 

Remember that the prototype is a proof-of-concept for the final game and not a
complete game in itself. Shaders or "special effects" are not expected at this
stage, and it's okay for mechanics to be disjointed or not fully integrated,
provided that they clearly reflect the vision outlined in the GDD.

### Submission

This is the final team submission and is the most important one to get right.
It is strongly recommended that you trial submitting (and check the online
WebGL build) at least a couple of times _comfortably before_ the deadline for
this milestone. As you add more features to your prototype, the odds of
something going wrong increase, so it's best to get ahead of any issues early.

> [!CAUTION]
> Double (and triple!) check that the latest changes to your project are in the
> `main` branch, and make sure this branch is being submitted on Gradescope. We
> will not be looking at other branches when marking.

Once again, follow the instructions under the [Gradescope
Submissions](#gradescope-submissions) section below in order to submit your
final work. Remember that the submission on Gradescope is what will be marked,
so ensure that you submit early and often to avoid any nasty surprises right
before the deadline. The GDD must also be in a "finalised" state by this point
and should reflect any changes made during the prototyping process.

Every member of your team is expected to verify that the submission on
Gradescope is visible to them, that all validation test cases pass, and that
the **final version** of the prototype (i.e. the one you want to be marked) can be
played in a browser via the link on the submission confirmation page. 

## Milestone 4: Team Member Evaluation
**Due: Sunday 21 September, 11.59 pm Melbourne time (individual submission)**

Teamwork is an essential part of the project, and it is possible for individual
group members to receive a different mark from that of the group. Most
importantly, **each person is expected to contribute to the project equally.**
We also expect that there is an effort to include all group members in the project
discussions and decision-making process. Therefore, we will be asking you to
evaluate your team members' contributions to the project, as well as provide a
self-evaluation of your own contributions.

After your team makes a submission for the final milestone, you are
individually required to submit a group member evaluation form for each of your
team members. This is conducted via a tool called FeedbackFruits, which you can
access [via the
LMS](https://canvas.lms.unimelb.edu.au/courses/239872/assignments/659412).

> [!WARNING]
> The group member evaluation is compulsory and must be submitted by the
> deadline. Failing to do so will be taken to be an indication that you have
> not contributed to the project, especially if team members have raised 
> concerns about your contributions. Marks will be adjusted accordingly.

The evaluation form will ask you to rate each team member on a rubric (scale of
1 to 5) using the following criteria:

- **Communication:** Refers to the quality of the group member's input in
  project discussions and their ability to facilitate effective communication.
  A good communicator provides meaningful input and contributes constructively
  to project discussions, be they in person or online.
- **Collaboration:** Refers to a group member's ability to work with others,
  respect their ideas, and promote balanced participation in discussions. This
  does not mean that all team members must agree on everything, but there
  should be a willingness to compromise and work together to achieve a strong
  outcome.
- **Contribution:** All team members are expected to contribute equally and
  pull their weight. A good contributor completes assigned tasks on time and
  shows overall commitment to the project.

Please take the time to provide thoughtful and constructive feedback for each
of your team members so that they are able to address concerns raised in the
next project (they will be able to see your feedback). The teaching team will
also use feedback provided in combination with the project repository history
to address concerns about unequal contributions. Marks will be adjusted
accordingly if it is found that a team member has not contributed as expected.

> [!IMPORTANT] 
> It is an expectation that you raise issues pertaining to your teammates *via
> the group member evaluation process* (not by email), so that they can see
> your feedback and have an opportunity to address it before starting Project
> 2. We also won't retrospectively adjust marks based on issues raised after the
> deadline for this milestone.

## Assessment

This assignment is worth 40% of your final mark. It will be assessed based on
the following criteria:

### 1. Game Design Document (14 marks) — *Group Mark*

#### Game Concept (5 marks)

- The game's concept should be clear, unique, and interesting, reflecting creativity and originality.
- The theme should be effectively addressed and integrated into the game's concept.
- The game mechanics should be well-defined, engaging, and (theoretically) fun.

#### Document Quality (5 marks)

- The `README.md` file in the provided template repository must be used to capture the Game Design Document.
- The document should be well-structured, well-written, easy to read, and formatted appropriately using GitHub Flavoured Markdown.
- The document should make liberal use of diagrams, sketches, links, and other visual aids to support the text.

#### Feasibility (4 marks)

- The game should be feasible to implement by the end of the semester, with a realistic and well-considered timeline until the final Assignment 2 deadline.
- Work should be clearly divided into tasks among team members, with clear strategies for time management, communication, and anticipating challenges.

### 2. Working Prototype Including Shaders (20 marks)

#### Game Prototype (8 marks) — *Group Mark*

- The input mechanisms should be functional enough to test the game prototype and experience its features.
- Camera orientation, positioning, and movement should be comfortable.
- The game prototype should be mostly consistent with the Game Design Document, with clearly visible and distinguishable objects (placeholder assets may still be used).
- The prototype should run correctly in WebGL without bugs or missing textures and maintain at least **30 FPS**.

#### Shader (12 marks) — *Individual Mark × (IOA Weight)*

- The shader should be non-trivial and custom-written for the game.
- The shader should appropriately enhance the game's visuals and potentially reduce CPU load.
- The shader should produce a distinct effect from the shaders created by other team members.

### 3. Project Organisation (6 marks) — *Group Mark × (FeedbackFruits Score)*

- The project should be well-organised and easy to navigate, with `Assets/StartScene.unity` as the entry point.
- The `Assets` folder must not exceed **250 MB** in size.
- All autograder validation tests must pass by each milestone deadline, and required workflow files must not be modified.
- All team members should regularly commit to the GitHub repository, with a process in place to avoid and resolve merge conflicts.
- All milestone deadlines must be met, including team member evaluations, and the project should demonstrate iterative development with the latest version on the `main` branch by each deadline.
- All guidelines in the assignment specification, including submission and late submission requirements, must be followed.

## WebGL Builds

Your game will eventually be deployed as a WebGL build, meaning that it can be
played in a web browser. This is the only deployment method that will be
supported for this project, and it won't be marked if it does not run in this
environment. You should regularly build locally, and also make periodic
submissions via Gradescope as outlined [below](#gradescope-submissions).

> [!CAUTION]
> If your project works within the Unity editor, this does not necessarily mean
> that it will work as a WebGL build. Build your game on a regular basis to
> ensure that it works as expected and that you're not dealing with unforeseen
> issues right before a deadline.

To build your game within Unity, go to `File > Build Settings > WebGL` (you
might need to "switch platform"), then click `Build and Run` and choose a
target folder. If the build is successful, Unity will create a simple local
webserver and open the game in your default web browser. For a detailed guide,
see [this page](https://docs.unity3d.com/Manual/webgl-building.html). 

**Avoid changing the WebGL build settings** that came with the template, as
this might lead to unexpected issues during marking. If you feel you must
modify something, ask the teaching team first. 

## Gradescope Submissions

A submission via Gradescope is required for every team-based submission
(milestones 1-3). To make a submission, complete the following steps:

1. For **Milestone 1**, The **team leader** must submit a single file on gradescope, which
   can be opened via the respective LMS assignment page. 
2. For **Milestone 2-3**, The **team leader** must submit the (Github) project repository on Gradescope. This will require
   linking their GitHub account to Gradescope if they haven't already done so.
4. Ensure that the GitHub repository is up-to-date and that the latest changes
   are merged into the `main` branch (if your team is using multiple branches).
6. The **team leader** should wait for the autograder to validate the
   submission, and ensure that all validation test cases pass. 
7. The **team leader** must then add all team members to the Gradescope submission.
   See [this
   guide](https://guides.gradescope.com/hc/en-us/articles/21863861823373-Adding-Group-Members-to-a-Submission)
   if you are unsure how to do this.
8. **All team members** are expected to verify that they can see the submission
   on Gradescope, that all test cases have passed, and that (for milestones 3
   and 3) the correct version of the game has been deployed (see below).
   If you're having issues, please contact the teaching team via a private post
   on the discussion board.

When you submit milestones 2 and 3, the Gradescope autograder will perform some
simple validation tests. If these pass, it will trigger a build in your team's
project repository using the **most recent** commit on the `main` branch and
attempt to deploy the build to GitHub pages (this process occurs within your
repository via GitHub actions). There will be a direct link to it on the
Gradescope submission confirmation page, once the autograder has finished
running.

**The build accessed via this link is the build that will be marked, so
verifying that this link on Gradescope opens your game as expected is
_essential_!** All team members are expected to do a check of the final
submission, and make sure that they are happy with what has been submitted. As
such, we will not be able to consider any issues raised after the deadline.

> [!NOTE]
> Builds can take a long time to complete, especially if there are a lot of
> assets. Take care to manage resources appropriately, and avoid including
> unnecessary assets or scenes in your project. 

## Late Submission Policy

Because this subject's assignments are all either group submissions or oral assessments, the usual Short Extensions (1-3 days) are not available for this subject, unless the student was granted Special Considerations or has an AAP. 

More information about this can be found here: [FEIT Extensions and Special Considerations](https://canvas.lms.unimelb.edu.au/courses/239872/pages/feit-extensions-and-special-considerations?module_item_id=7578500)

>[!WARNING]
> All deadlines indicated are strict. The penalty for late submission of Milestone 2 and 3 is 10% of the total available marks (3 marks) per day or part thereof, up to a maximum of 5 days. 
> After this time, late submissions will not be accepted. Milestone 4 will not accept late submission (the peer review portal automatically shuts). 
> Failure to submit will be taken to be an indication that you have not contributed to the project, and penalties may apply as a result.

## Academic Honesty

Every member of your team is expected to follow the University's Academic Integrity policies. To ensure that you properly attribute work that is not your own, your team must:

- Include a "References" section at the end of your repository's README.md outlining all external resources used.
- For code or game logic, you must also include comments within the respective sourcecode files providing direct link(s) to the sources utilised.
- If you use an AI tool to support secondary tasks such as polishing text or generating concept art for the GDD, you must cite it in your README.md file (under the "references" section), and outline exactly how it was used.
- You must not use AI to author the components that are directly assessed for your own technical and analytical skill. In the group project this includes the game concept and ideas described in the GDD, and the custom Cg/HLSL shader programs.

Submitting work that a member of your team has not authored, without proper attribution, is considered academic misconduct. Also bear in mind that heavy reliance on external resources may result in a lower mark, as it is difficult to assess your own understanding of the concepts involved.

More information is available here: [Academic Integrity Expectations and Information](https://canvas.lms.unimelb.edu.au/courses/239872/pages/academic-integrity-expectations-and-information?module_item_id=7578505)

### Unity Asset Store

Use of the Unity asset store is _strictly_ limited to importing artistic assets. In
simple terms - images, models, animations, sounds and music tracks are fine,
but not code, components, game logic, or non-artistic prefabs. Note that it is
possible to get a great mark without using "flashy" external resources! You are
assessed based on what you create, and how well you address the criteria in
this specification. In other words, producing a fun and well-polished game with
consistent visuals is much more important than sourcing "AAA game" assets.

### Credit where credit is due ...

Remember, we expect that a majority of your submission is your team's
regardless. Full credit will not be awarded where there is an over-reliance on
others' work, even if it is attributed. We will be checking for similarity
between submissions and with code available over the Internet.

## Resources and Help

Check out the following resources for help with this project:

- [GitHub Markdown](https://guides.github.com/features/mastering-markdown/) - A
  comprehensive guide to "GitHub Flavoured" Markdown, the formatting language
  used in `README.md` (your GDD).
- [Unity Learn](https://learn.unity.com/) - Unity's official learning platform,
  with tutorials and courses for all skill levels.
- [Unity Documentation](https://docs.unity3d.com/Manual/index.html) - Unity's
  official documentation, with detailed information on all aspects of the
  engine.

If you can't figure something out or are unsure about something in the
specification, feel free to reach out to your tutor or post on the discussion
board.
