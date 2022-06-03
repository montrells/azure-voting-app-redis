pipeline{
    agent any

    stages{
        stage('Verify Branch Lets go'){
            steps{
                echo "$GIT_BRANCH"
            }
        }
//         stages{
//             steps{
//                 pwsh(script: 'docker images -a')
//                 pwsh(script: """
//                     cd azure-vote/
//                     docker images -a'
//                     docker build -t jenkins-pipeline .
//                     docker images -a
//                     cd ..
//                     """)
//             }
//         }
    }
}
