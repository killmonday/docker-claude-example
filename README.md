容器中如果Claude code没有安装成功，可能是ip被官网识别为不支持地区，可直接执行 .devcontainer/install.sh 进行安装。
或执行 `curl -fsSL https://claude.ai/install.sh | bash ` 安装。

进入容器终端使用 `su vscode` 和 `bash` 进入普通用户并进入交互式shell。
若claude安装后没有自己把二进制目录加入 .bashrc，可自己执行 `echo "export PATH=\"\$HOME/.local/bin:\$PATH\"" >> ~/.bashrc`
