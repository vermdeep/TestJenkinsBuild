pipeline {
  agent any
  triggers { pollSCM('* * * * *') }
  stages {
    stage('Build project') {
       steps {
        echo 'Run Unit Tests'
        echo 'test 2'
        echo 'test3'
      }
    }

    stage('Deploy ZDev') {
        steps {
            echo 'skipping zdev deployment.'
echo "test5"
        }
    }
  }
}

