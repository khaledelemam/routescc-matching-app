-e pk# YOUR PRODUCT/TEAM NAME
> _Note:_ This document is meant to evolve throughout the planning phase of your project.   That is, it makes sense for you commit regularly to this file while working on the project (especially edits/additions/deletions to the _Highlights_ section). Most importantly, it is a reflection of all the planning you work you've done in the first iteration. 
 > **This document will serve as a master plan between your team, your partner and your TA.**

## Product Details
 
#### Q1: What are you planning to build?

 > Short (1 - 2 min' read)
 * Start with a single sentence, high-level description of the product.
 * Be clear - Describe the problem you are solving in simple terms.
 * Be concrete. For example:
    * What are you planning to build? Is it a website, mobile app,
   browser extension, command-line app, etc.?      
    * When describing the problem/need, give concrete examples of common use cases.
    * Assume your the reader knows nothing about the problem domain and provide the necessary context. 
 * Focus on *what* your product does, and avoid discussing *how* you're going to implement it.      
   For example: This is not the time or the place to talk about which programming language and/or framework you are planning to use.
 * **Feel free (and very much encouraged) to include useful diagrams, mock-ups and/or links**.

#Answer
We plan to build a matching app that finds drivers to help clients in need.
Currently, Routes Connecting Communities manually find volunteer drivers and contact them. This process is time consuming and unreliable.
We are going to build an app that finds reliable and convenient matchings between clients in need and drivers. 
Our algorithm will be based off of data provided on location, preferences and availability times.
This app will be a desktop app since it will be used at the RoutesCC office for office purpose only. 




#### Q2: Who are your target users?

  > Short (1 - 2 min' read max)
 * Be specific (e.g. a 'a third-year university student studying Computer Science' and not 'a student')
 * **Feel free to use personas. You can create your personas as part of this Markdown file, or add a link to an external site (for example, [Xtensio](https://xtensio.com/user-persona/)).**


#Answer
Our target user is volunteer drivers and employees at the office of Routes Connecting Communities. 
A 70 year old volunteer driver that is looking to help someone by driving them to the hospital.
A 40 year old employee at the RoutesCC office that wants to find an available volunteer driver to take Anne to the dentist this weekend.

#### Q3: Why would your users choose your product? What are they using today to solve their problem/need?

> Short (1 - 2 min' read max)
 * We want you to "connect the dots" for us - Why does your product (as described in your answer to Q1) fits the needs of your users (as described in your answer to Q2)?
 * Explain the benefits of your product explicitly & clearly. For example:
    * Save users time (how much?)
    * Allow users to discover new information (which information? And, why couldn't they discover it before?)
    * Provide users with more accurate and/or informative data (what kind of data? Why is it useful to them?)
    * Does this application exist in another form? If so, how does your differ and provide value to the users?
    * How does this align with your partner's organization's values/mission/mandate?

#Answer
A user will use this product that does not want to spend time guessing the right volunteer driver and 
contacting them just to find out they are not available. The user that uses this app to find a driver for a job that is geographically close,
meets the driver's preferences and is flexible for the driver's schedule. An employee will use this app to quickly
find the right volunteer driver for each client in need. The app will parse the database of clients and drivers to find the best
matching for each client.

#### Q4: How will you build it?

> Short (1-2 min' read max)
 * What is the technology stack? Specify any and all languages, frameworks, libraries, PaaS products or tools. 
 * How will you deploy the application?
 * Describe the architecture - what are the high level components or patterns you will use? Diagrams are useful here. 
 * Will you be using third party applications or APIs? If so, what are they?
 * What is your testing strategy?

Our app will need to connect to the database of clients and drivers using an API provided by RoutesCC.
We will use the Google API to find the distance between two addresses.
We will deploy the application as
Our testing strategy will be writing test cases for the expected matchings given the data.
We will test all types of data to ensure our output matching is convenient.


#### Q5: What are the user stories that make up the MVP?

 * At least 5 user stories concerning the main features of the application - note that this can broken down further
 * You must follow proper user story format (as taught in lecture) ```As a <user of the app>, I want to <do something in the app> in order to <accomplish some goal>```
 * User stories must contain acceptance criteria. Examples of user stories with different formats can be found here: https://www.justinmind.com/blog/user-story-examples/. **It is important that you provide a link to an artifact containing your user stories**.
 * If you have a partner, these must be reviewed and accepted by them



----
## Intellectual Property Confidentiality Agreement 
> Note this section is **not marked** but must be completed briefly if you have a partner. If you have any questions, please contact David and Adam.
>  
**By default, you own any work that you do as part of your coursework.** However, some partners may want you to keep the project confidential after the course is complete. As part of your first deliverable, you should discuss and agree upon an option with your partner. Examples include:
1. You can share the software and the code freely with anyone with or without a license, regardless of domain, for any use.
2. You can upload the code to GitHub or other similar publicly available domains.
3. You will only share the code under an open-source license with the partner but agree to not distribute it in any way to any other entity or individual. 
4. You will share the code under an open-source license and distribute it as you wish but only the partner can access the system deployed during the course.

**Briefly describe which option you have agreed to. Your partner cannot ask you to sign any legally binding agreements or documents pertaining to non-disclosure, confidentiality, IP ownership, etc.**

----

## Process Details

#### Q6: What are the roles & responsibilities on the team?

Describe the different roles on the team and the responsibilities associated with each role. 
 * Roles should reflect the structure of your team and be appropriate for your project. Not necessarily one role to one team member.

List each team member and:
 * A description of their role(s) and responsibilities including the components they'll work on and non-software related work
 * 3 technical strengths and weaknesses each (e.g. languages, frameworks, libraries, development methodologies, etc.)

Rogan -
Haocheng - 
Pawanpreet - Java, Python, Writing test cases, Making or designing a user friendly GUI. Weakness: Front end on Web using html/css
Valerie -
Welvin -
Khaled -

#### Q7: What operational events will you have as a team?

Describe meetings (and other events) you are planning to have. 
 * When and where? Recurring or ad hoc? In-person or online?
 * What's the purpose of each meeting?
 * Other events could be coding sessions, code reviews, quick weekly sync meeting online, etc.
 * You must have at least 2 meetings with your project partner (if you have one) before D1 is due. Describe them here:
   * What did you discuss during the meetings?
   * What were the outcomes of each meeting?
   * You must provide meeting minutes.
   * You must have a regular meeting schedule established by the second meeting.  
  
  
 We will have online weekly meetings. The purpose of the meetings is to get everyone's feedback and express concerns. It will also consist of 
 discussing the progress made in the week and plans for the next week. It is to ask our partner questions and discuss the choices to make.
 The goal is to keep everyone up to date with the project with everything that is going on in the project. We will also discuss how much everyone
 will be able to contribute in the upcoming week.
 
#### Q8: What artifacts will you use to self-organize?

List/describe the artifacts you will produce in order to organize your team.       

 * Artifacts can be To-Do lists, Task boards, schedule(s), meeting minutes, etc.
 * We want to understand:
   * How do you keep track of what needs to get done?
   * **How do you prioritize tasks?**
   * How do tasks get assigned to team members?
   * How do you determine the status of work from inception to completion?


We will use a text file in our repos that has user stories with the priorities and status and owners of the user stories.
If a user story has not been taken, a team member is free to take it and indicate the time it will take to finish it.
We also have a discord server for open communication and to keep everyone engaged and up to date.

Our tasks will be assigned in our weekly team meeting. 
Tasks will be suggested to team members as a group and will be assigned to a member with the selected member's agreement.
Each member can express their interest for a user story. By the end of the meeting, we will agree to an assignment of user stories
to each team member. It can change over the week before the next team meeting by discussing any difficulty in our team chat.

#### Q9: What are the rules regarding how your team works?

Describe your team's working culture.

**Communications:**
 * What is the expected frequency? What methods/channels are appropriate? 
 * If you have a partner project, what is your process (in detail) for communicating with your partner?
 
**Meetings:**
 * How are people held accountable for attending meetings, completing action items? Is there a moderator or process?
 
**Conflict Resolution:**
 * List at least three team scenarios/conflicts you discussed in lecture and how you decided you will resolve them. Indecisions? Non-responsive team members? Any other scenarios you can think of?

We will have a process of questions that we must go through in each meeting. We can pick a moderator to lead the process,
before starting this process in the meeting. Refer to the previous question Q8's answer for details on the progress.

Scenario: A team member was not able to complete most of their weekly assigned work.
The team member is expected to let the team know through the team chat. If it is a busy week coming up, team member can let the team 
know while we assign user stories during the meeting.

Scenario: A team member is not responding and did not come to the team meeting

Scenario: Multiple team members want a user story, or a team member does not want to do their user story

Scenario: 


----
## Highlights

Specify 3 - 5 key decisions and/or insights that came up during your meetings
and/or collaborative process.

 * Short (5 min' read max)
 * Decisions can be related to the product and/or the team process.
    * Mention which alternatives you were considering.
    * Present the arguments for each alternative.
    * Explain why the option you decided on makes the most sense for your team/product/users.
 * Essentially, we want to understand how (and why) you ended up with your current product and process plan.
 * This section is useful for important information regarding your decision making process that may not necessarily fit in other sections. 

