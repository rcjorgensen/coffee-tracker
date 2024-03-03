# coffee-tracker
Never run out of coffee again ☕

# Kotlin Quick Start

## Install SDKMAN

```sh
curl -s "https://get.sdkman.io" | bash
```
Restart terminal.

## Install Java 

```sh
sdk install java 21.0.2-tem
```

## Install Kotlin

```sh
sdk install kotlin
```

## Write "Hello, World!" program

```sh
echo 'fun main() { println("Hello, World!") }' > hello.kt
```

### Compile

```sh
kotlinc hello.kt -include-runtime -d hello.jar
```

### Run

```sh
java -jar hello.jar
```

