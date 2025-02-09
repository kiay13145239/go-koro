# go-koro

This project tries to build a CI platform that can be used to manage daily, presubmit and postsubmit jobs like Kokoro, a Google internal CI tools, by using Golang, Kubernates and Docker.

Reasons why I choose to use Docker and Kubernates come from my experiences when using Kokoro at the time I am being a Extended Workforce in Google, and the major problems I faced are waste of resources and failure when getting intensive tasks because Kokoro itself did not re-allocate occupied resources directly, which made executed jobs get stuck or be ignored under certain conditions.

Therefore, to fix those mentioned issues and enhance the performance in automatic way, this project would use a combination of Golang, a programming language which is famous of handling high concurrency problems, Docker, a well-known containerization tool that can build several containers once a machine has suitable resources, and Kubernates, an open-source container orchestration system for automating software deployment, scaling, and management.

As a maintainer, to achieve expected functionalities, will try to complete tasks below when developing this project.

- (In Progress)List out pros and cons of Kokoro
- Understand capability of Golang, Kubernates and Docker
- Design the full architecture of tool
- Develop required functionalities based on desired OS and environment
