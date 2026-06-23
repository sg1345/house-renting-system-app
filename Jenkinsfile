pipeline{
    agent any
    stages{
        stage("Restore Packages"){
            steps{
                bat "dotnet restore"
            }
        }
           
        stage("Build"){
            steps{
                bat "dotnet build"
            }
        }
        stage("Test"){
            steps{
                bat "dotnet test"
            }
        }   
    }
}
