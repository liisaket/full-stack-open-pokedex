Let's reflect on the tools I could use when coding an application with Python. For linting I would use Pylint, which is an effective tool to check that the code is clean i.e. there are no errors and it is readable. I have used Pylint in my previous coding experience. By googling I also found similar tools to Pylint, which are Flake8 and Ruff.

For testing the code, which is a very important step in coding in general, I would use Pytest and Unittest. Pytest is flexible as you can do all sorts of tests with it, including unit tests and end-to-end tests. With unittest you can test your functions and classes.

"Building" the code means putting all of the code together into runnable software. For Python this is not needed. But it can be a helpful step, to make sure the code runs, all tests pass and it builds the whole code into one so you can publish the whole application. Some Java build tools I found are Maven and Gradle.

Some alternatives for setting up the CI/CD besides Jenkins and GitHub Actions are Spacelift, GitLab CI and Azure DevOps.

The difference between a self-hosted and cloud-based setup, are flexibility and controllability. With a self-hosted setup like Jenkins, you can control pretty much everything, and with cloud-based setup you can just tell the service what to do and no need to worry about all the settings. I do not have much experience with self-hosted setups, so I would prefer the cloud-based environment.

References:

- the course material https://fullstackopen.com/en/part11/introduction_to_ci_cd
- java build https://code.visualstudio.com/docs/java/java-build
- jenkins alternatives https://spacelift.io/blog/jenkins-alternatives
- python linting and testing https://realpython.com/python-code-quality/#applying-best-practices-for-high-quality-code-in-python
