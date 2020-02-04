pipeline {
    agent any
    parameters {
        string(name: "Greetings", defaultValue: "Hello", description: "How should I great")
    }
    stages {
        stage("Example") {
            steps {
                echo "${params.Greetings} World!"
            }
        }
    }
}
