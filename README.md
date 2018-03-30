# aeg-kube-poc
My k8s poc


# Pushing Images

Taken from: https://cloud.google.com/container-registry/docs/pushing-and-pulling

      # Do this in gcloud console

      # to get the project ID use:
      $ gcloud projects list

      $ docker tag  docker tag [SOURCE_IMAGE] [HOSTNAME]/[PROJECT-ID]/[IMAGE][:TAG]
      $ docker tag  tgilkerson/ping-svr:test us.gcr.io/kube-poc-1/ping-svr:test
      $ docker push us.gcr.io/kube-poc-1/ping-svr:test
