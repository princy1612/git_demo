node
{
    stage('check out')
    {
       checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/princy1612/git_demo.git']]]) 
    }
    stage('anyalsis of code')
    {
        echo "Anyalsis the code"
    }
    stage('build the  code')
    {
        echo "Builded  the code"
    }
    stage ("testing the code")
    {
        echo " test the code"
    }
}
