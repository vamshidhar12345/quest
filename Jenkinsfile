pipeline {
agent any
stages {
stage ('Compile Stage') {
steps {
bat 'mvn clean compile'
}
}
stage ('Testing Stage') {
steps {
bat 'mvn test'
}
}
stage ('Packaging  Stage') {
steps {
bat 'mvn package'
}
}
}
} 

