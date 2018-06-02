pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('Compilacion') {
            steps {
                  script {
                      currentBuild.displayName = "The name."
                      currentBuild.description = "The best description."
                  }
                 sh 'mvn clean install'
            }
        }
    }
}
