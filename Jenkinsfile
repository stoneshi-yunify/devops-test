pipeline {
  agent any
  parameters {
        booleanParam(name: 'refresh', description: '通过 Gradle --refresh-dependencies 参数进行 Jar 包强制刷新')
    }

  stages {
    stage('echo ') {
      steps {
        script {
          sh 'echo ${refresh}'
        }

      }
    }
  }
}
