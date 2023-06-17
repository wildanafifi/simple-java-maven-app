node {
    docker.image('maven:3.9.0-eclipse-temurin-11') {
        stage('Build') {
            sh 'mvn -B -DskipTests clean package'
        }
        stage('Test') {
            sh 'mvn test'
        }
    }
}