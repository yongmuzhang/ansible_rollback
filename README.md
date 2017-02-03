# ansible_rollback
利用ansible达到快速回滚到某个已发布版本

# 使用命令
例如, 回滚到前一个版本:ansible-playbook -f 1 rollback.yml -e "v=1"
