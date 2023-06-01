node('nodejs') {
    stage('Backend Tests') {
        sh 'ls -las'
        sh 'node ./backend/test.js'
    }
    stage('Frontend Tests') {
        sh 'node ./frontend/test.js'
    }
}
