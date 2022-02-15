pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
      stage('test'){
        steps{
          echo'GoodMorning, U R in Test'
        }
      }
      stage('prod'){
        steps{
          echo'U R in Prod'
          build quietPeriod: 4, job: 'job1'
        }
      }
    }
}
