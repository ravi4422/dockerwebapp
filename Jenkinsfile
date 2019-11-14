node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'admin') {

        def customImage = docker.build("ravi4422/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
