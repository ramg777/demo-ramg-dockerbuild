This respository contains the source of the poetry application and docker file to build the docker image. The build of the docker image is written in Github actions pipeline.

    -> The pipeline triggers when code is reviewed and merged to the main branch or if there is any direct push to main branch.
    -> It builds the docker image and push the image to the repository.
