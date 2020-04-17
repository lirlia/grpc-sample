# grpc-sample

This replository is a sample for gRPC client/server.

server has 3 service.

* SayHello
* SayHelloAgain
* CalcBMI

## requirement

* python 2.7
  
## preparement

```
pip install -f requirement.txt
```

## run server 

```
python greeter_server.py
```

## run client 

```
python greeter_client.py
```

if you want to change `proto` please run cmd

`python -m grpc_tools.protoc -I.--python_out=. --grpc_python_out=. helloworld.proto`
