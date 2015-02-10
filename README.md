Groupify Front-end Design
===

Introduction
---
This is the front-end design and code of project Groupify, which is an educational web application in development. --- by Junyu Wang

Progress
---
Page Structure, Course index page, Group/Topic index page, post index page, post/course/group create form have finished.

To Do
---
post show page, repy form.

Demo
---
This is the course index page, where all courses are listed
![course index][courseIndex]
[courseIndex]: screenshot/course-index-page.png

This is when we hover one of the course, the course panel is flipped and course introduction, join button show up
![course index toggle][courseIndexToggle]
[courseIndexToggle]: screenshot/course-index-toggle.png

On the left sidebar, there's a create course button, by clicking that you will be directed to the course creation Page
![course creation][courseCreate]
[courseCreate]: screenshot/course-create-form.png

After you join one of the courses, you get access to it and by clicking the "Go" button (which should appear at the same location as "Join" after you join this course) you will be directed to the page containing topics and group information.
![topic/group index][topicGroupIndex]
[topicGroupIndex]: screenshot/group-topic-index-page.png

And as you might have noticed, on the top bar there's a "Toggle" button, this button lets you expand the size of the content page.
![topic/group index left toggle][topicGroupIndexLeftToggle]
[topicGroupIndexLeftToggle]: screenshot/group-topic-index-left-toggle.png

When you hover over one of the topic, the topic panel buzzes out (which can't be shown here), and when you hover one of the group button, its corresponding topic shows up.
![group hover toggle][groupHoverToggle]
[groupHoverToggle]: screenshot/group-hover-toggle.png

When you clicked one of the graph button, a modal with its name, corresponding topic's name and content pops out.
![group show][groupShow]
[groupShow]: screenshot/group-show-toggle.png

If you are an instructor account (which is true in this demo) you should see "watch" and "delete" in the modal, if you are a student you shoul expect to see "Go" instead. By click either "watch" or "Go", you get into the page contains the posts, topic, student answer and instructor answer of the topic, like a online discussion platform.
![post index][PostIndex]
[PostIndex]: screenshot/post-index-page.png 

And if you click one of the post, its title and content will pop out.
![post show][postShow]
[postShow]: screenshot/post-show-toggle.png


