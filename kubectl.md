# kubectl

Loading auto completion.
```
sudo apt-get install bash-completion
source <(kubectl completion bash)
```

Run busybox Pod with curl installed and start shell.
```
kubectl run -n kafka curl --image=radial/busyboxplus:curl -i --tty
```

Create autoscaling deployment.
```
kubectl autoscale deployment <deployment_name> --cpu-percent=50 --min=1 --max=10
```
