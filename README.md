# Portfolio
 for Fontys Semester 3 individual project by Aleksa Bandic

## Table of Contents
- [Portfolio](#portfolio)
  - [Table of Contents](#table-of-contents)
- [Intro](#intro)
- [Sprint recaps](#sprint-recaps)
- [Self-assessment](#self-assessment)
  - [Web Application](#web-application)
  - [Software Quality](#software-quality)
  - [Agile Methodology](#agile-methodology)
  - [CI/CD](#cicd)
  - [Cultural Differences and Ethics](#cultural-differences-and-ethics)
  - [Requirements and Design](#requirements-and-design)
  - [Business Processes](#business-processes)
  - [Professional](#professional)

# Intro

This is a collection of all documentation regarding my individual project. Besides documents for SneakPeak, this repo will also host my individual research papers, hosted in the [research-papers](https://github.com/sneakpeak-git/sneakpeak-documentation/tree/main/research-papers) folder.

# Sprint recaps

## First sprint

The first sprint did not have a determined date and during it I didn't really do much since I was focusing heavily on my group project. That is not to dismiss the importance of the individual project however, it was just a matter of priority distribution and I know I need more focus on the individual project moving forward.
During this sprint I did research on the stack I would like to use, and I settled on Expo for frontend and Express.js for backend, as I really enjoyed using React Native in my group project and wanted to improve my skills. Expo is a React Native framework, it is very popular and easy to work with and using it is going to mean better maintainability of the project, as it is not just popular but also cross platform, being able to build web, Android and iOS apps with the same codebase. Express.js is a Node.js web application framework, also really popular.

## Second sprint

My second sprint marked the actual beginning of my individual project work, both codebase and documentation wise. During this sprint, my main goal was to estabilish a good foundation for my documentation, both on GitHub and JIRA. I created repos for different components in my GitHub organization, set up a profile page and wrote descriptions of features and instructions on how to set up the development requirement and run the project. Additionally, I started to organize work by user stories and tasks on JIRA. I started coding the frontend app, only using mock data at the moment.

For the next sprints, I am planning to make them shorter and more feature-packed, since I think I can handle the workload now that I got the hang of the documentation and tracking my progress. I want to speed up my workflow since the semester is coming to a close relatively and I would like to prove myself. I will be keeping the latest self-evaluation grades below this.

## Third sprint

During this sprint I started working on the Sneaker API and touched up the frontend app. Data API fetches sneakers from a MySQL database and returns them in a legible format. Learning how to use Node with Sequelize to get the database data was the main focus point of this sprint.

## Fourth sprint

This sprint was all about CI/CD. I containerized my Data API using Docker Compose along with a MySQL database and automatized the process of storing database credentials and creating tables, so that it can be done without user input in the Docker environment. I also created a basic test workflow with GitHub Actions that runs a few integration tests using Mocha and Chai.

## Fifth sprint

Sprint five is where I perfected the CI process by improving the test workflow, adding code coverage, linting using ESLint and Prettier and code analysis with SonarCloud. I learned a lot about test workflows and how to make sure the app works in a fresh environment on every single run.

## Sixth sprint

This is the final sprint and perhaps the most feature-packed one. I switched to React from Expo for frontend because of integration issues with SSO and the Expo Go app. I implemented SSO using Firebase Authentication as well as integrated Cypress for frontend E2E testing. Some improvements were made to the Data API too, with it now being able to return individual sneakers and handle errors better. A lot of work has been done on the documentation side of things to wrap up the semester nicely.

# Self-assessment

The following table contains my views on the current standing of the project regarding different learning outcomes.

Ratings go from '*Undefined*', to '*Orienting*', to '*Beginning*', '*Proficient*' and finally to '*Advanced*', on a scale of 1 to 5. 

## Web Application

<table>
  <tr>
    <th><strong>Learning Outcome</strong></th>
    <td>"You desgin and build user-friendly, full-stack web applications."</td>
  </tr>
  <tr>
    <th><strong>Proficiency Rating</strong></th>
    <td>Proficient</td>
  </tr>
  <tr>
    <th><strong>Explanation</strong></th>
    <td>
        --
    </td>
   <th><strong>Proof</strong></th>
    <td>
        --
    </td>
  </tr>
</table>

## Software Quality

<table>
  <tr>
    <th><strong>Learning Outcome</strong></th>
    <td>"You use software tooling and methodology that continuously monitors and improve the software quality during software development."</td>
  </tr>
  <tr>
    <th><strong>Proficiency Rating</strong></th>
    <td>Proficient-Advanced</td>
  </tr>
  <tr>
    <th><strong>Explanation</strong></th>
    <td>
        --
    </td>
   <th><strong>Proof</strong></th>
    <td>
        --
    </td>
  </tr>
</table>

## Agile Methodology

<table>
  <tr>
    <th><strong>Learning Outcome</strong></th>
    <td>"You choose and implement the most suitable agile software development method for your software project."</td>
  </tr>
  <tr>
    <th><strong>Proficiency Rating</strong></th>
    <td>Proficient</td>
  </tr>
  <tr>
    <th><strong>Explanation</strong></th>
    <td>
        --
    </td>
   <th><strong>Proof</strong></th>
    <td>
        --
    </td>
  </tr>
</table>

## CI/CD

<table>
  <tr>
    <th><strong>Learning Outcome</strong></th>
    <td>"You design and implement a (semi)automated software release process that matches the needs of the project context."</td>
  </tr>
  <tr>
    <th><strong>Proficiency Rating</strong></th>
    <td>Advanced</td>
  </tr>
  <tr>
    <th><strong>Explanation</strong></th>
    <td>
        --
    </td>
   <th><strong>Proof</strong></th>
    <td>
        --
    </td>
  </tr>
</table>

## Cultural Differences and Ethics

<table>
  <tr>
    <th><strong>Learning Outcome</strong></th>
    <td>"You recognize and take into account cultural differences between project stakeholders and ethical aspects in software development."</td>
  </tr>
  <tr>
    <th><strong>Proficiency Rating</strong></th>
    <td>Proficient</td>
  </tr>
  <tr>
    <th><strong>Explanation</strong></th>
    <td>
        --
    </td>
   <th><strong>Proof</strong></th>
    <td>
        --
    </td>
  </tr>
</table>

## Requirements and Design

<table>
  <tr>
    <th><strong>Learning Outcome</strong></th>
    <td>"You analyze (non-functional) requirements, elaborate (architectural) designs and validate them using multiple types of test techniques."</td>
  </tr>
  <tr>
    <th><strong>Proficiency Rating</strong></th>
    <td>Proficient</td>
  </tr>
  <tr>
    <th><strong>Explanation</strong></th>
    <td>
        --
    </td>
   <th><strong>Proof</strong></th>
    <td>
        --
    </td>
  </tr>
</table>

## Business Processes

<table>
  <tr>
    <th><strong>Learning Outcome</strong></th>
    <td>"You analyze and describe simple business processes that are related to your project."</td>
  </tr>
  <tr>
    <th><strong>Proficiency Rating</strong></th>
    <td>Proficient</td>
  </tr>
  <tr>
    <th><strong>Explanation</strong></th>
    <td>
        --
    </td>
   <th><strong>Proof</strong></th>
    <td>
        --
    </td>
  </tr>
</table>

## Professional

<table>
  <tr>
    <th><strong>Learning Outcome</strong></th>
    <td>"You act in a professional manner during software development and learning."</td>
  </tr>
  <tr>
    <th><strong>Proficiency Rating</strong></th>
    <td>Proficient</td>
  </tr>
  <tr>
    <th><strong>Explanation</strong></th>
    <td>
        --
    </td>
   <th><strong>Proof</strong></th>
    <td>
        --
    </td>
  </tr>
</table>
