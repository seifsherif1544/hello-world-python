pipeline {
    agent any

    stages {

        stage ('unit test') {

            steps {
                sh '''#!/bin/bash

                    echo "Hello from unit test"

                    docker build -t Dockerfile
                
                '''
            }
        }
    }
}
