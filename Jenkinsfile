pipeline {
  agent any
  stages {
    stage('') {
      steps {
        zip(zipFile: 'pipeline.zip', archive: true, dir: 'deliver')
        mail(subject: 'Pipeline activated', body: 'jenkins uat test pipeline', to: 't.vaghjee@linkbynet.com', from: 'Jenkins-uat@lbn.fr')
      }
    }
  }
}