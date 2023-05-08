# DH110 Assignment 5: Low Fidelity Prototype by Haryn Shin
## Introduction
**Description of the project:** 

The current project aims to enhance the connections among family members by providing a shared journaling space where they can comfortably share their life, thoughts, and emotional experiences with each other through journaling. Through such shared, collaborative journaling app, family members can form their own private journaling space and interact with each other in a deeper level.

Through user-research, I found that there could be two major purposes for the shared journaling app that I intend to create: first, users who are physically distant from their family members who yearn to stay in touch and keep the connections strong; second, users who want to effortlessly keep records of their valuable memories spent with their family. Based on these two user groups, I created two personas, one pertaining to the first user group and the other pertaining to the second user group described above. 

You can find the complete user research process, personas, their respective scenarios, and journey maps through these links: 
- [User Research: Contextual Inquiry](https://github.com/harynshin/DH110-HARYNSHIN/blob/main/Assignments/A3_Contextual_Inquiry.md)
- [Personas & Scenarios](https://github.com/harynshin/DH110-HARYNSHIN/blob/main/Assignments/A4_persona_scenario.md)


**Purpose of the low-fidelity prototype:**

The purpose of the low-fiedlity prototype is to visualize the idea of the app by creating basic outlines and structures, and test their functionalities with a user by observing potential issues and difficulties in navigating through the app. 

**User tasks for prototype testing:**

In the process of testing the low fidelity prototype, users were instructed to complete the following tasks:
1. Write a journal entry about your summer plans and upload photos from your photo album to the journal entry
2. Invite a member to your shared journal
3. Search for journal entries that contain the word "vacations"
4. Find pictures that “Mom” posted from the Gallery tab
5. Put a reaction emoji of your choice and write a comment to a journal entry by "Mom"

## Initial Wireframes & Wireflow
The initial wireframes and wireflows are as follows:

![wireframes + wireflows](https://user-images.githubusercontent.com/116034969/236704614-9887d837-bf73-47ca-b12b-8274e7a00228.svg)
_Link (for a more detailed view)_: [Wireframes wireflows figma link](https://www.figma.com/file/d58V0amDpYZeiMJq0Q1uKt/dh110-lofi-wireframes%2Fflows-haryn-shin?type=whiteboard&node-id=0%3A1&t=yn49WeZcRLSapcam-1)

**Wireframes & Wireflow Description**
#### Initial Prototype Flow
- User enters the "Bond" (journal) that they want to enter 
- Feed: shows the journal entries that user and the members of the share journal wrote, with the most recent journal entry on top
  - The date tab leads to a calendar page where user can view journal entries that were posted on a specific date
  - User can click on the pencil icon on the top right of the feed page to write a journal entry
  - User can search for keywords in the journal and search for journal entries that contain the searched keyword through the magnifying glass icon on the top right corner
  - User can click the three dots to view journal members, invite new member, and the journal name and description
  - User can click the "read more" button under each journal entry on the feed to view the whole text, leave a reaction emoji, and comment on the specific journal entry
- Chat: user can chat with specific members of the journal 
- Gallery: user can view all the photos/ videos posted along with the journal entries at once like a "family gallery"
  -  user can sort the photos by newest to oldest, oldest to newest, and by the owner of the photos
- Profile: user can edit their display name, profile picture, and bio description for the specific journal

## Prototype Testing
### Initial prototype
With the initial prototype design, I proceeded to use the wireframes that mainly corresponded to the 5 user tasks that were proposed above during the prototype testing. The following displays the steps that the user took to complete all the tasks. 

![Interation 1 (1)](https://user-images.githubusercontent.com/116034969/236708807-ef0d3f47-fbd5-402a-bbdf-aa5cc5231b86.svg)
_Link (for a more detailed view)_: [Iteration figma link](https://www.figma.com/file/Laf1jYTv7yBGFdt1KSWM9y/dh110-a5-iteration-1-haryn-shin?type=whiteboard&node-id=0%3A1&t=2vpIflc6KXE1aOq7-1)

*The boxes and arrows indicate what the user clicked on and what it led to during the prototype testing

**What went smoothly:**
- Overall, the user was able to complete all five tasks with relative ease. Most of the times, the user was able to easily locate the icons that they were looking for and quickly realize with each icon meant (pencil icon for writing, plus for adding, magnifying glass for searching, etc). For the most part, the low-fidelity prototype was clear and easy to use for the user, especially in terms of how the functionalities were consistent and followed the standards of other typical apps. 
- Specifically, the user was able to complete task 1 and 3 without any issues and claimed that the ways to complete these tasks were apparent and straightforwardly depicted on the wireframes. 

**What went different/ unexpectedly & user feedback:**

Some difficulties in testing the prototype was that because these prototypes were digital, the user had to get used to how Figma worked -- for instance, the user had some difficulty in writing out their journal entry using the text tool. Moreover, as the prototypes were low fidelity, displaying the most basic outlines and only the essential features and functionalities, the user had some difficulty in recognizing some simplified buttons or display (for instance, how photos and videos are just shown as boxes with an X on them). Besides these minor adjustment difficulty of the user getting used to the digital low-fidelity prototype on Figma, there were some potential issues that came up with the design of the prototype itself which impeded the user from completing the tasks in ways that I expected, which are as follows.
- Task 2: user struggled with the task of locating the feature of adding/ inviting members to their journal since the user assumed that the three-dots menu icon would lead to settings. The three-dots icon was not as clear, and it would be better if it was replaced by an icon that is more clear and intuitive to the user in terms of adding new members to the journal.
- Task 4: Though user was able to complete this task easily, user suggested an important feedback during the task: the current way of displaying photos in the gallery sorted by owner could lead to an infinite scroll, and as photos pile up, users would have to scroll unnecessarily many times to reach to the photos of the particular member that they were looking for. The first alternative to the current way the photos are displayed was to make a folder or an album for each owner and store their content within each of their albums, so that users can click on the owner's album first, then find photos that they uploaded inside their album. A second alternative that I thought of was to make an additional feature on the side where users can search or filter by a specific owner that they were looking for, by, for example, check-boxing that specific owner from the side bar. 
- Task 5: Instead of clicking the "read more" button to view a member's full journal entry, the user tried to click the journal entry box itself in order to read the full text. Such action of the user suggested that the "read more" button is not as clear to the user and should be more visible and explicit, and also that I should give users the freedom to click on the journal entry box and still lead to the wanted outcome of viewing the full journal entry. 
- Task 5: While trying to write a comment on a member's journal entry, user was confused how there were two comment options "Go to comments" and the pencil icon to write a comment. Originally, the idea was that if user clicks on "Go to comments", they would be able to view all the comments on a separate page, while if they click the pencil icon, they would be able to write a comment. Being confused by the two options, user chose the "Go to comments" option to write their comment and not the pencil icon. This suggested that there were two unnecessarily repetitive comment options on the current prototype and should fix it by eliminating one of the comment options and make it more clear to the user in terms of how to write a comment on a member's journal entry.

### Revised Prototype
Based on the first prototype testing and user's feedback, I revised the previous prototype as such: 

![revision (2)](https://user-images.githubusercontent.com/116034969/236900746-83e2b312-1154-4c72-864a-0f2fbc2d5892.svg)
_Link (for a more detailed view)_: [Revision figma link](https://www.figma.com/file/dNtU242wc4EdrZkswAQvAO/dh110-revised-prototype-haryn-shin?type=whiteboard&node-id=0%3A1&t=tB4TggkZ4DwXcS8w-1)

*The box, arrows, and marks that are presented in red show the changes that I have made based on the initial prototype testing

## Revised Wireframes & Wireflow
The full revised wireframes and wireflows are as follows:
![wireframes + wireflows final](https://user-images.githubusercontent.com/116034969/236936614-f037acc3-d30b-468d-a34e-5d9fea2c368c.svg)
_Link (for a more detailed view)_: [Wireframes wireflows figma link](https://www.figma.com/file/d58V0amDpYZeiMJq0Q1uKt/dh110-lofi-wireframes%2Fflows-haryn-shin?type=whiteboard&node-id=0%3A1&t=yn49WeZcRLSapcam-1)

## Reflection
As shown above, the user was able to complete all five tasks proposed with relative ease, with a few confusing points during the prototype testing. 
