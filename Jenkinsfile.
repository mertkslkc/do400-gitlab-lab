pipeline {
agent any
stages {
stage('Test') {
parallel {
stage('Unit tests') {
steps {
sh './mvnw test -D testGroups=unit'
}
}
}
}
}
}
