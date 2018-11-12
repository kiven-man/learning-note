# learning-note
# docker 批量删除镜像 
docker rmi $(docker images | grep "none" | awk '{print $3}') 
