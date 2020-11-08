pipeline {
  agent any
  stages {
    stage('Development') {
      steps {
        echo 'Development Complete'
      }
    }

    stage('QA') {
      steps {
        git 'https://github.com/LeafPages/Salesforce'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deployment Completed'
      }
    }

  }
}