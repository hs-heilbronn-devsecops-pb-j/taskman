<a href="https://codeclimate.com/github/hs-heilbronn-devsecops-pb-j/taskman/test_coverage"><img src="https://api.codeclimate.com/v1/badges/e0c196beb209a7f221e8/test_coverage" /></a>
[![Run test suite on PR](https://github.com/hs-heilbronn-devsecops-pb-j/taskman/actions/workflows/pull-request-test.yaml/badge.svg)](https://github.com/hs-heilbronn-devsecops-pb-j/taskman/actions/workflows/pull-request-test.yaml)
# Taskman

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/hs-heilbronn-devsecops-pb-j/taskman)

# Testing from the command line

## Create a new task

```
curl --request POST --url http://localhost:8000/tasks \
  --header 'Content-Type: application/json' \
  --data '{"name": "my name", "description": "my description"}'
```


