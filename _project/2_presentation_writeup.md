---
layout: page
title: final demo and writeup
permalink: /presentation-and-project/
description: final submission- demo and writeup
nav: true
nav_order: 2
hw_pdf: project-description.pdf
assigned: september 9, 2024
due_date: december 9, 2024
horizontal: false
---

<hr style="border:2px solid gray">

<br>

Create a finished, deployable solution with a front end that leverages a model project with user interface, served on GCP. The following are some ideas of example projects:

* **Anomaly Detection** - Enter in a new document. What is the probability that his document belong? 
* **Information Retrieval** - Use a corpus of distinct elements. From a query, return a fine-tuned result.
* **Topic Modeling** - In set of documents (maybe of multiple languages), enable exploration via topic.
* **Sentiment Analysis** - Enter in a new tweet or movie review. Is it positive or negative? How confident?

Feel free to pick any topic that you have data for. You can form groups of up to four; in your writeup, have a contributions sections denoting what each member worked on. There are two components to your project: your writeup and your code. 

<br>
-----

#### starter kit and artifacts

The following are the artifacts that we will turn in via Gradescope.

* [Project Writeup](https://www.overleaf.com/read/kszvtsstmnfs) (PDF Format)
  - Why is it important and interesting (review [heilmeier catechism](https://www.darpa.mil/work-with-us/heilmeier-catechism))?
  - How is your technical approach dealing with the complexity of the data?
* [Project Repository](http://www.github.com) (Github Repository via Link)
  - Include a README.md on how to setup and run the project. This should be straightforward.
  - Try to containerize your solution with Docker so we don't need specific libraries or software.
* [Demonstration](http://streamlit.io) (DNS unnecessary)
  - This does not need to have continued uptime 100%. We will access your server (and it can be an IP address)

<br>
-----

#### rubric and criterion

There are two components your project: its presentation and your technical delivery. This delivery will come in the form of a real-time demonstration of your engineering. In order to receive credit, your **must have a real-time inference** component. The delineation between the two contributions will be graded on the following.

|---|---|---|
|---|---|---|
| 33% | : | __Documentation__ : Written and oral delivery of project rationale and justification of approach
|     | - | &nbsp;&nbsp;&nbsp;&nbsp; Motivation and Impact: A future iteration of this project can make a difference
|     | - | &nbsp;&nbsp;&nbsp;&nbsp; Background and Related Work: Project is well-researched within and beyond course scope
|     | - | &nbsp;&nbsp;&nbsp;&nbsp; Modeling Methodology: Robustness to pitfalls like class imbalance and overfitting
|     | - | &nbsp;&nbsp;&nbsp;&nbsp; Evaluation and Analysis: Justification of the approach is sound
| 66% | : | __Technical__ : Demonstration of your work, handling of corner cases, technical correctness
|     | - | &nbsp;&nbsp;&nbsp;&nbsp; Base Accessibilty: The endpoint is open and is accessible to the public
|     | - | &nbsp;&nbsp;&nbsp;&nbsp; Performant: Results arrive in a reasonble time, and path to additional scaling is apparent
|     | - | &nbsp;&nbsp;&nbsp;&nbsp; Data Scale: Data needs to have at least 10k rows of meaningful amount of data
|     | - | &nbsp;&nbsp;&nbsp;&nbsp; Replicable: Algorithms must be replicable and containerized

<br>

#### presentation and grading

Each team will have five minutes to introduce their project (slides are not necessary). Prior to this, they will need start their servers so that the demonstration can commence. Instructor and TA's will operate the end-point in real-time from their laptops.

<br>

-----
#### submission instructions
-----

Add the link to your project to [the final lecture slide deck](https://docs.google.com/presentation/d/1VO-SAmfm3smmDhVn6AkyK-SZTDURDILz9xCFx_0OiAA). (This is slide 2.) Commit all your code to your repository, and submit via [Gradescope](https://www.gradescope.com/). There, you will upload your PDF and provide the link to your repository, which should have all the code that you used to generate your solutions. Please submit only __once__ per team by including all persons on Gradescope.



<!--
<br><br><br>
<hr style="border:2px solid gray">
#### project checkpoint
-----
-->


