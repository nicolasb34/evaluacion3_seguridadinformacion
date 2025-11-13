pipeline {
    agent any
    stages {
        stage('Clonar repositorio') {
            steps {
                echo 'El pipeline ha obtenido el código desde GitHub correctamente.'
            }
        }
        stage('Verificar entorno') {
            steps {
                sh 'echo "Verificando que Jenkins está ejecutando el pipeline..."'
                sh 'python3 --version || echo "Python no está instalado en este contenedor Jenkins."'
            }
        }
        stage('Finalización') {
            steps {
                echo 'Pipeline ejecutado con éxito 🎉'
            }
        }
    }
}
