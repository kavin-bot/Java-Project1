pipeline{
    agent any

  stages{
    stage("clean the workspace"){
        steps{
            script{
                cleanWS()
            }
        }
    }
    stage("code checkouts"){
        steps{
            script{
                gitCheckout{
                    branch: "main"
                    url: "https://github.com/kavin-bot/Java-Project1.git"
                }
            }
        }
    }
    /*stage("unit test"){
        steps{
            script{

            }
        }
    }
    stage("integration test"){
        steps{
            script{

            }
        }
    }
    stage("code analysis"){
        steps{
            script{

            }
        }
    }
    stage("Quality check"){
        steps{
            script{

            }
        }
    }
    stage("Maven Build"){
        steps{
            script{

            }
        }
    }
    stage("Docker Build"){
        steps{
            script{

            }
        }
    }
    stage("Docker push"){
        steps{
            script{

            }
        }
    }
    // integrate with argocd and publish the application
    stage("Update and push in deployment"){
        steps{
            script{

            }
        }
    } */
  }

}