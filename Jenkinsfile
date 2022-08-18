pipeline{
    agent any
    stages{
        stage("test1"){
        steps{
            echo "trying to get this"
        }
        }
        stage("test2"){
        steps{
            echo "I need practice"
        }
        }
        stage("test3"){
        steps{
            mail bcc: '', body: 'Did it work', cc: '', from: '', replyTo: '', subject: 'This is a test email from Shanese jenkins', to: 'shanesehogg@gmail.com,aguyton01@gmail.com'
        }
        }
    }
}
