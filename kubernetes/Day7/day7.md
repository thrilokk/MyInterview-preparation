In day7 we are going to learn Pod and fundmentals of YAML

# Pod
We will be starting complete handson of pod from day7

- Two different ways we can create a pod in kubernetes cluster
    1. imperative
    2. Declarative

- In imperative which you run simple commands such as kubectl run pod, basically we are instructing to API Server or with kubectl utility like do this creation or run or delete pods by using imperative way 

- To use Declarative, we use configuartion file like Json or YAML
- Yaml is heavily used in kubernetes
- Json is hardly used in kubernetes

but both can support

As part of Declarative approach, we create a configuration file and you set deesired state of the object in the files
    examples:
        1. I need to use particualr API version
        2. need to create pod with custom name
        3. need to use particular image

