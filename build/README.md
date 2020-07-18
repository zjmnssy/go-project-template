# build目录说明
- 打包和持续集成。
- 把你的 cloud (AMI), container (Docker), OS (deb, rpm, pkg) 包配置和脚本放入/build/package目录。
- 把你的 CI (travis, circle, drone) 配置和脚本放入build/ci目录。注意，一些 CI工具 (e.g., Travis CI) 对它们的配置文件位置特别挑剔。可以将它们的配置文件放在/build/ci目录， 然后创建文件链接到这些工具希望的位置。
