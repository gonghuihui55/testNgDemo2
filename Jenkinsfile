pipeline{    agent any    stages{        stage('build'){            //mvn构建            steps{                //sh 'export PATH="/var/jenkins_home/apache-maven-3.6.1/bin:${PATH}'                sh "ls -la"                sh "pwd"                sh "/var/jenkins_home/apache-maven-3.6.1/bin/mvn clean install -Dmaven.test.skip=true"            }        }        stage('deploy'){            steps{                //执行部署脚本                echo "deploy ......"            }        }    }}