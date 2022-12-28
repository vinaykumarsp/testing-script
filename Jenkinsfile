pipeline{
  agent any
  stages{
    stage(BDD){
      steps{
        echo "BDD testing"
        sh "chmod +x ./betest.sh"
        sh "./betest.sh"
      }
    }
  }
}
