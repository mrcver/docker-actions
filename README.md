#Docker Github Action 云编译demo

此操作将通过`docker`进行`image`编译，然后将编译好的`image`推送到`hub.docker.com`

最终产物可以拉取镜像验证： `docker pull wataly/actions:hello`

```shell
$ docker run wataly/actions:hello
Hello, Bye-bye~~
$
```