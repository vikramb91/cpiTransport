@Library('piper-lib-os') _

node() {
  stage('init') {
    deleteDir()
    checkout scm
  }
  stage('transportIntegrationArtifact Command') {
       integrationArtifactTransport script: this
  }
}
