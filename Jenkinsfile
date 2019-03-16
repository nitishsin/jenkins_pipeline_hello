node
{
    stage('build')
    {
        echo "building"
    }
}

stage('Get Approval for Testing')
{
    input "IS Build ready for test?"
}

node
{
   stage('test')
    {
        echo "testing"
    }
}

stage('Get approval')
{
    input "Deploy to qa?"
}

node
{
    stage('deploy to qa')
    {
        echo "deploying to QA"
    }
}

stage('Get approval for Prod deployment')
{
    input "Is buid ready for prod deployment ?"
}

node
{
    stage('Deploy to Prod')
    {
        echo "Deploying to Prod"
    }
}
