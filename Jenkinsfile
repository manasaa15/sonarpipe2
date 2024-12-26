node {
  stage('Build') {
    echo "Building"
  }
  stage('Test') {
    echo "Testing"
  }

  // Check the build result
  if (currentBuild.currentResult == 'SUCCESS') {
    echo "Looks good"
  } else {
    echo "Failed"
  }
}
