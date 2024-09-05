# sync-docker-image
#### 同步docker镜像到阿里云镜像仓库ACR

## Fork 后配置 Repository secret
#### [Settings] -> [Secrets and variables] -> [Actions] -> [New repository secret]
    - ALIYUN_REGISTRY     // 阿里云仓库地址
    - ALIYUN_NAMESPACE    // 阿里云命名空间(开启自动创建仓库)
    - DOCKER_USERNAME     // 用户名
    - DOCKER_PASSWORD     // 密码

---

将需要同步的镜像写入 docker-images.txt 提交即可同步

