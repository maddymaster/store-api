# store-api
Building the backend(REST API) of a maketplace, however, implementing
1. Docker
2. Coding best practices that follow PEP8 - integrating Flake8 lint test
3. TravisCI for continuous build and deploy
4. TDD - test driven development
5. Mocking

To run this file, first build docker-compose and then run the docker.

Note: To run tests use --rm as it would remove the container after test. For example "docker-compose run --rm app sh -c "python manage.py test && flake8"

Visit the url 127.0.0.1:8000/admin to visit admin page.

PS: I have paused working on this for a while due to increased workload at office.
