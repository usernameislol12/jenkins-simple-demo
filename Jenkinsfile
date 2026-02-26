pipeline{
  agent any
  staes{
    stage('Clone'){
      git url: 'https://github.com/usernameislol12/jenkins-simple-demo.git',
        branch: 'main'
    }
  }
  stage('Run Script'){
    steps{
      sh 'chmod +x script.sh'
      sh './script.sh'
    }
  }
}
}
