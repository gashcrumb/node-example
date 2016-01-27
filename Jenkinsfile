node ('kubernetes'){
  git 'git@github.com:gashcrumb/node-example.git'
  withEnv(["PATH+MAVEN=${tool 'maven-3.3.1'}/bin"]) {

    sh 'mvn clean install'
  }
}
