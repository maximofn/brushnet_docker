# brushnet_docker
BrushNet docker


# ml-mgie docker

Dockerization of the [Hugging Face BrushNet Space](https://huggingface.co/spaces/TencentARC/BrushNet)

 * Page: [BrushNet](https://tencentarc.github.io/BrushNet)
 * Repository: [BrushNet](https://github.com/TencentARC/BrushNet)
 * Space: [TencentARC/BrushNet](https://huggingface.co/spaces/TencentARC/BrushNet)

## Requisites

[Docker](https://docs.docker.com/desktop/) and [nvidia container toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html) must be installed.

## Usage

You can download the image and run it

```bash
docker pull maximofn/brushnet:latest
./run_app.sh
```

### Build the image

Or you can build the image and run it

```bash
./build_docker_image.sh
./run_app.sh
```