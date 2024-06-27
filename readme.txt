# 拉取镜像
docker pull ghcr.io/coder/code-server
docker pull ghcr.io/coder/code-server:4.90.3-39

# 启动服务
docker run --name code-server -d -p 6001:8080 -v D:/workspace_js/remote_code_server:/home/coder ghcr.io/coder/code-server

# 本地访问
http://localhost:6001

# 远程访问
http://localhost:6001

# 登录密码配置
D:\workspace_js\remote_code_server\.config\code-server\config.yaml
