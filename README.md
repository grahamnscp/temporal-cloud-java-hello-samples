# Temporal java hello samples updated to run on Temporal Cloud

## Reference source:
ref: https://github.com/temporalio/samples-java/tree/main/core/src/main/java/io/temporal/samples/hello

## Environment
Sample direnv .envrc file provided with classpath using target in maven pom.xml  
export CLASSPATH="./target/dependency/*:./target/hellosamples-1.0.jar"

## Build
Might need to tweek for java versions etc or use ide :)
```
mvn compile
mvn verify
mvn dependency:copy-dependencies
```

## Run samples
```
java hellosamples.HelloActivity
java hellosamples.HelloActivityExclusiveChoice
java hellosamples.HelloActivityRetry
java hellosamples.HelloAsync
java hellosamples.HelloAsyncActivityCompletion
java hellosamples.HelloAsyncLambda
java hellosamples.HelloCancellationScope
java hellosamples.HelloChild
java hellosamples.HelloCron
java hellosamples.HelloDetachedCancellationScope
java hellosamples.HelloDynamic
java hellosamples.HelloException
java hellosamples.HelloLocalActivity
java hellosamples.HelloParallelActivity
java hellosamples.HelloPeriodic
java hellosamples.HelloPolymorphicActivity
java hellosamples.HelloQuery
java hellosamples.HelloSaga
java hellosamples.HelloSchedules
java hellosamples.HelloSearchAttributes
java hellosamples.HelloSideEffect
java hellosamples.HelloSignal
java hellosamples.HelloUpdate
```
