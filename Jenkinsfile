@Library('mpl@release') _

MPLPipeline {}

// Use default master pipeline
MPLPipeline {}
{ProjectRepo}/.jenkins/modules/Deploy/Deploy.groovy: 
// Any step could be here, config modification, etc.
echo "Let's begin the deployment process!"

// Run original deployment from the library
MPLModule('Deploy', CFG)

echo "Deployment process completed!"
