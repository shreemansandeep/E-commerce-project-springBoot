pipeline{
  
  agent any
  
  stages{
    
    stage('Git Checkout'){
      steps{
        git branch: 'main', credentialsId: 'GitID', url: 'https://github.com/shreemansandeep/E-commerce-project-springBoot.git'
      }
    }
    
    stage('Git Checkout'){
      steps{
        sh 'mvn clean package'
      }
    }
    
    
  }
}
