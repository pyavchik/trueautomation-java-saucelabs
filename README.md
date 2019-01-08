# trueautomation-java-saucelabs

You must have: <br>
installed TrueAutomation client, JDK 8 or later. <br>
account at saucelabs.com

## How to run test:

* Checkout project

 ```
 git clone https://github.com/pyavchik/trueautomation-java-saucelabs.git
 ```
* Set up your username and access key:
```
public static final String USERNAME = "USERNAME";
public static final String ACCESS_KEY = "ACCESS_KEY";
```
* Init project use `trueautomation init` command
 
* Run test

```bash
mvn -Dtest=exampleTest test

```