node {
 stage('SCM Checkout') {
   git 'https://github.com/quickbooks2018/Learning-Jenkins/tree/master/my-app-master'
 }
 stage('Compile-Package') {
 //Get Maven Home Path
   def mvnHome = tool name: 'maven3', type: 'maven'
   sh "${mvnHome}/bin/mvn package"
 }
}
