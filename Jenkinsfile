properties([pipelineTriggers([pollSCM('* * * * * ')])])
node("test"){
    stage("execute"){
        bat "c:\\Users\\kmalikin\\AppData\\Local\\Programs\\Python\\Python39\\python NewButton.py"
    }
	stage("execute2"){
        bat "c:\\Users\\kmalikin\\AppData\\Local\\Programs\\Python\\Python39\\python NewScreen.py"
    }
}
