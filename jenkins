node{
    stage('SCM Checkout'){
      git 'https://github.com/jitpack/maven-simple'
    }
    stage('Complie-Package'){
      sh 'mvn package'
    }
}
