pipeline{
agent any
  stages{ 
stage('maven install') {
  steps {
    // One or more steps need to be included within the steps block.
    withMaven(maven: 'maven3') {
    // some block
    sh  'mvn clean install'
    }
  }
  }
}
}
