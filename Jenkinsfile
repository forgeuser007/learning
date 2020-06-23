node {
  stage 'Checkout'
  git url: 'https://github.com/forgeuser007/learning.git'

  stage 'build'
  docker.build('webserver')

  stage 'deploy'
  sh './deploy.sh'
}
