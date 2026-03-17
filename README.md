# Postman API Workflows

This repository contains automated API tests created using Postman CLI. Originally developed as a personal learning project, it demonstrates practical experience with API automation, workflow integration, and testing best practices.

Although this project was a practice exercise, the techniques used are directly applicable to professional projects involving APIs, including integrations with client platforms, third-party services, and internal tools.

## Overview

- **Automated Testing:** Runs API tests automatically on GitHub Actions whenever code is pushed.  
- **Postman CLI:** Uses Postman CLI to execute collections reliably.  
- **Reusable Workflows:** Demonstrates how to structure and maintain automated API test workflows for any project.

## Workflow Details

1. GitHub Action triggers on push events.  
2. Postman CLI is installed in the runner environment.  
3. Secure login using an API key stored in GitHub Secrets.  
4. Executes the designated Postman collection:


## Business Relevance

This project highlights skills that are valuable in a professional context:

- Efficient API testing and automation for web applications.  
- CI/CD integration to ensure API reliability.  
- Ability to implement repeatable, maintainable testing workflows for client or internal projects.

Even as a past practice project, this repository reflects practical experience with tools and methods that can support business solutions, system integrations, and software reliability initiatives.

## How to Use

1. Fork or clone this repository.  
2. Add your Postman API key to GitHub Secrets (`POSTMAN_API_KEY`).  
3. Push code to trigger the automated tests.  
4. Review results directly in GitHub Actions.

---

*Demonstrates real-world API workflow experience that complements business projects and client solutions.*
