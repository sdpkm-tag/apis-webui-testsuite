# apis-webui-testsuite
A comprehensive test suite for apis and web application

### Important links
- [Official TCases Github Repo](https://github.com/Cornutum/tcases)


### Pre-requisites and preparing the test-suite
#### OpenAPI document based tests
- Prepare / copy or upload the API definition / OpenAPI yaml file in `${baseDir}/srs/test/tcases/...` root directory. 
### Commands
#### - Commands to run OpenAPI tests based on yaml definition, this will also generate a basic `HTML Report` in the `${baseDire}/target/tcases/...` directory
```
$ mvn clean tcases:api -Dhtml=true
```

