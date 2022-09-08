node{
  stage('SCM Checkout'){
    git 'https://github.com/vennabharath/sampl.git'
  } 
  
  stage('Compile package'){
    sh 'mvn package'
  }
}
