pipeline {
  agent any
  tools {
    maven 'M3'
    jdk 'JDK11'
  }

  stages {
    stage('Git Clone') {
      steps {
        git url: 'https://github.com/kyd2506/spring-petclinic.git', branch: 'efficient-webjars', credentialsid: 'gitCredentials'
    }
   }
  }
  
}
