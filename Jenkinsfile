node
{
stage 'download-from-github'
sh "echo download"

stage 'execute_tests'
sh "echo test"

stage 'package'
sh "echo package"

stage 'deploy'
sh "echo deploy"

stage 'execute ansible'
sh "echo ansible"
  
stage 'approval'
input 'Do you want to proceed'
}
