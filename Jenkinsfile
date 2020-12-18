pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '798eeb05-1b7b-4a8e-b7b4-98fb2f9cddc7', url: 'https://github.com/narmadha687/mycab.git']]])
            }
        }
        stage('compilation') {
            steps {
                echo 'compilation done'
            }
        }

    }
}