#!/usr/bin/groovy

node {

  stage("First stage") {
    echo "This stage takes 5 seconds"
    sh "echo Something"
    sh "sleep 5"
    echo "Done"
  }

  stage("Second stage") {
    echo "This stage takes 15 seconds"
    echo "Doing some stuff..."
    sh "sleep 15"
    echo "Done"
  }

  stage("Third stage") {
    echo "This stage takes 30 seconds"
    echo "More stuff..."
    sh "sleep 30"
    echo "Done"
  }

  stage("Final stage") {
    echo "Doing that last thing takes 5 seconds"
    sh "sleep 5"
    echo "Done"
  }

}