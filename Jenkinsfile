node {
   stage('scm') {
    git 'https://github.com/isansharma/game-of-life.git'
   }

   stage('Build'){
       def mvnHome = tool 'LocalMaven'
       sh '${mvnHome}/bin/mvn package'
   }
}
