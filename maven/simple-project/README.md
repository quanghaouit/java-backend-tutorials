### Relevant Articles
- [Guide to the Core Maven Plugins](https://www.baeldung.com/core-maven-plugins)
    + Maven defines 3 build Lifecicles:
        * Default: reponsible for all steps in the build process, from project validation to package deployment
        (process-resources -> compile -> process-test-resources -> test-compile -> test -> package -> install -> deploy)
        * Site: In charge of building a site, showing maven related information of the project
        * Clean: Take care of removing files generated in the previous build

- [Maven Resources Plugin](https://www.baeldung.com/maven-resources-plugin)
    + Resources plugin copies files from input resource directories to an output directory. This plugin have 3 goals:
        * resources - copy resource that are part of the main source code to the main output directory
        * testResources - copy resource that are part of the test source code to the test output directory
        * copy-resources - copy arbitary resource files to an output directory, requiring us to specify the input files and the output directory

- [The maven compiler plugin](https://www.baeldung.com/maven-compiler-plugin)
    + Use to compile the source code of a Maven project. This have 2 lifecycle
        * compile - compile main source files
        * testCompile - compile test source files

- [Quick Guide to the Maven Surefire Plugin](https://www.baeldung.com/maven-surefire-plugin)
    + Use to test
- [The Maven Failsafe Plugin](https://www.baeldung.com/maven-failsafe-plugin)
    + Use to integration test
- [The Maven Verifier Plugin](https://www.baeldung.com/maven-verifier-plugin)
    + Use to verify file/directory exist
- [The maven install plugin](https://www.baeldung.com/maven-install-plugin)
    + Use to add artifacts to the repository and it automatically
- [Maven deploy plugin](https://www.baeldung.com/maven-deploy-plugin)
    + Pushing artifacts to a remote repository to share with other developer
- [The Maven Clean Plugin](https://www.baeldung.com/maven-clean-plugin)
- [Build a Jar with Maven and Ignore the Test Results](https://www.baeldung.com/maven-ignore-test-results)
- [Maven Project with Multiple Source Directories](https://www.baeldung.com/maven-project-multiple-src-directories)
- [Integration Testing with Maven](https://www.baeldung.com/maven-integration-test)
- [Apache Maven Standard Directory Layout](https://www.baeldung.com/maven-directory-structure)
- [Multi-Module Project with Maven](https://www.baeldung.com/maven-multi-module) 
*** ADVANCE ***
- [Maven proxy](https://maven.apache.org/guides/introduction/introduction-to-profiles.html)
    + Profiles in Maven help us to configure properties that'll be active when our application is deployed to different environments.
- [Setting maven proxy](https://www.baeldung.com/maven-behind-proxy)
    + Configure Maven to work behind a proxy
- [Settiing maven ](https://www.baeldung.com/maven-enforcer-plugin)
    + The enforce goal runs during a project build to execute rules specified in the configuration
- [Update dependency lastest version](https://www.baeldung.com/maven-dependency-latest-version)
    + Allow to exploit the Versions Maven Plugin to keep our dependencies up-to-date.
- [Create maven plugin](https://www.baeldung.com/maven-plugin)    