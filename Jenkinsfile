pipeline {
agent any
stages {
stage('Install Dependencies') {
steps {
sh 'pip3 install -r requirements.txt'
}
}
stage('Run Tests') {
steps {
sh 'python3 -m unittest'
}
}
}
}

pipeline {
agent any
stages {
stage('Install Dependencies') {
steps {
sh 'pip3 install -r requirements.txt'
}
}
stage('Run Tests') {
steps {
sh 'python3 -m unittest'
}
}
}
}


correct the indentation of syntax for copy paste
