pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        git(url: 'ssh://git@10.1.2.83:2222/zhwmac/test.git', branch: 'master')
      }
    }
    stage('deploy') {
      steps {
        sh '''cd /tmp
mkdir github
echo 1 > gitHub/a.txt'''
      }
    }
  }
}