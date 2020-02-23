node {
    stage('clone') {
        git 'git@github.com:seckbass/jenkins.git'
    }
    
    stage('build') {
        sh label: '', script: 'javac Main.java'
    }
    
    stage('run') {
        sh label: '', script: 'java Main'
    }
}
