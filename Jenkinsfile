pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo $testbed
echo $vcd_build'''
      }
    }
  }
  environment {
    vcd_build = '12345'
    testbed = 'testbed.json'
  }
}