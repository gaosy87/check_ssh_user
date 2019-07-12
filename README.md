# check_ssh_user

# 安装依赖包
pip install paramiko==2.0.8

# 语法
python check_ssh_user.py ip username –port 22

# 验证说明
如果服务器存在的用户，则脚本会返回Valid username
如果服务器不存在的用户，则脚本会返回Invalid username
