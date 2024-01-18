# sample-circle-ci

## config validation
```
circleci config validate
```

## local execution

❗️ need to commit code changes before execution.

```
circleci local execute <job name>
```

To set config file to run

```
circleci local execute --config .circleci/e2e_test.yml test
```
