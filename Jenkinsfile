pipeline {
  agent any
  stages {
    stage('Create OKE Cluster') {
      steps {
        sh '''#!/bin/sh
echo "Stage1"'''
      }
    }
    stage('Deploy 2 OKE') {
      steps {
        sh '''#!/bin/sh
echo "Stage2"'''
      }
    }
    stage('Validate OKE deployment') {
      steps {
        sh '''#!/bin/sh
echo "Stage3"'''
      }
    }
    stage('Cleanup Cluster') {
      steps {
        echo 'Cleanup'
      }
    }
    stage('Cleanup OKE') {
      steps {
        echo 'cleanup oke'
      }
    }
  }
}