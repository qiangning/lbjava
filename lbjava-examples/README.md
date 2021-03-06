# LBJava examples 

Here are a couple of sample classification projects which are using LBJava.

1. [Entity Relations Classification](src/main/java/edu/illinois/cs/cogcomp/lbjava/examples/entityRelation/README.md)
2. [Set Cover Problem](src/main/java/edu/illinois/cs/cogcomp/lbjava/examples/setCover/README.md)
3. [Badges Classification](src/main/java/edu/illinois/cs/cogcomp/lbjava/examples/badges/README.md)
4. [Newsgroup Classification](src/main/java/edu/illinois/cs/cogcomp/lbjava/examples/newsgroup/README.md)
5. [Spam Classification](src/main/java/edu/illinois/cs/cogcomp/lbjava/examples/spam/README.md)
6. [Sentiment Classification](src/main/java/edu/illinois/cs/cogcomp/lbjava/examples/sentiment/README.md)
7. [Regression Classification](src/main/java/edu/illinois/cs/cogcomp/lbjava/examples/regression/README.md)

## How to run 

From the root directory, run the appropriate commands:

To generate *lbj* to *java* and compile examples:

```
mvn compile
```

To compile and train all examples:

```
mvn compile -P train-all-examples
```

To compile individual examples:

```
mvn compile -P train-<example-name>
```

Available profile names are: `badges`, `entity`, `newsgroup`, `sentiment`, `setcover`, `spam`, `regression`.

Example: ```mvn compile -P train-spam``` for the generating and training just the Spam classifier example.




