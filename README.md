#Test Case:
- use SimpleTestCase - no database
- use TestCase - Database

*import objects to test
*define test class
*add test method
*setup inputs
*execute code to be tested

#Build and Run
docker-compose build
docker-compose run --rm app sh -c "python manage.py startapp core"