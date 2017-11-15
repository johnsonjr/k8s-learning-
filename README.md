k8s-learning 

gcloud compute instances list 
gcloud compute ssh <Name-Server>

gcloud config set compute/zone us-central1-b


gcloud config list

gcloud container clusters create k8s-cluster
gcloud container clusters create kubernetes-lab1  --machine-type n1-standard-1   --num-nodes 2

gcloud container clusters create k8s-cls  --machine-type n1-standard-1   --num-nodes 2

-----------------------------------------------------------------------------------------------------------------------------------
gcloud auth list

gcloud config list project

sudo /google/google-cloud-sdk/bin/gcloud components update

gcloud config set project PROJECT_ID

gcloud config set compute/zone europe-west1-d 

gcloud config set container/cluster kubernetes-lab1

gcloud container clusters get-credentials kubernetes-lab1

Credentials will be stored in ~/.kube/config.

kubectl cluster-info


