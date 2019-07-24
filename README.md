# Demo test suites for Robotframework

## Run test suites locally
`robot --outputdir=./output-local --variable HEADLESS_BROWSER_ENABLED:False robot-tests/selenium-library`

## Generate the test case documentation
`python3 -m robot.testdoc robot-tests output-local/keywords.html`

## Generate the keyword documentation
`python3 -m robot.libdoc robot-tests output-local/keywords2.html`

## Run test suites in docker
`docker-compose up`
