pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'mvn -f hello-app/pom.xml -B -DskipTests clean package'
            }
           
        }
    }
}
