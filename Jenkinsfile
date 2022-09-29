pipeline {
    agent {
        label {
            label "built-in"
        }
    }
    stages{
        stage( "stage-1" ){
            steps{
                echo "This is 1st Pipeline"
            }
        }
        stage("parelle"){
            parallel{
                stage ("stage-2"){
            steps{
                echo " This is 2nd pipeline"
            }
        }
        
        stage ("stage-3"){
            steps{
                echo"This is 3rd pipeline"
            }
        }
            }
        
        }
    }
    
    
}
