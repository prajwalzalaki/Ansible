pipeline {
  agent any
  stages {
    stage('Fetch the playbook') {
      steps {
        git(url: 'https://github.com/prajwalzalaki/Ansible.git', branch: 'master', changelog: true, poll: true)
      }
    }

  }
}