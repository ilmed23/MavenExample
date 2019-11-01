node ('Slave_1'){
    stage ('build'){
    git credentialsId: 'gitcreds', url: 'git@github.com:ilmed23/MavenExample.git'
    sh 'mvn package'
    }
}
