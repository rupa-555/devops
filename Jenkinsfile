pipeline {
agent any
stages
{
stage('Checkout'){
steps{
//pull code from git 
git branch: 'new1' ,url: 'https://github.com/rupa-555/devops.git'
}
}
stage('Build'){
steps{
echo 'Building project'
}
}
stage('Test')
{
steps{
echo 'running  tests'
}
}
stage('deploy')
{
steps{
ech0 'Deploying '
}
}
}
}
