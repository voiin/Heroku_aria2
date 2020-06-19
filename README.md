# Heroku aria2c

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## 使用Rclone将下载的文件同步到您的云驱动器

1.按照以下官方说明设置Rclone：https：//rclone.org/docs/
2.找到您的rclone.conf文件，它应如下所示：
[DRIVENAME]
type = WHATEVER
client_id = WHATEVER
client_secret = WHATEVER
scope = WHATEVER
token = WHATEVER

others entries...
3.找到您要使用的驱动器，然后将其复制type = ...到 ... token = ...部分。
4.将所有换行符替换为 \n
5.使用上方的按钮进行部署，然后将该文本粘贴到 RCLONE_CONFIG
6.设置RCLONE_DESTINATION为您要存储下载文件的路径。
