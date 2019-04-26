node {
    checkout([$class: 'GitSCM', branches: [[name: '*/master']],userRemoteConfigs: [[url:'https://github.com/mynameissunny/java.git'], [credentialsId: '73c4541e-b696-435e-9091-7985b90a8f45']]])
    
    stage("go build"){
        sh "echo testing"
    }
    stage("go test"){
        sh "echo testing 2"
    }
} 
