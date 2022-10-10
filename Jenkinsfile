pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'We are Starting the Init steps2'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project2'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area2"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area2"
                  }
            }
      }
}
