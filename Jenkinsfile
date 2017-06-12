pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
                sh './testbash.sh'
                sh '~/learn-jenkins/pipeline-1/testbash.sh'
                sh '/home/ramesh/learn-jenkins/pipeline-1/testbash.sh'
            }
        }
    }
}
