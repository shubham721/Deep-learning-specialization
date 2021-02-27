# Deep-learning-coursera
Material for deep learning course which I had done on coursera


command to split
tar -czf - ~/work | split --bytes=100MB - ~/workspaces.tar.gz

rm -f ~/workspace.tar.gz && rm  -f ~/work/workspace.tar.gz
tar -czf ~/workspace.tar.gz ~/work
mv ~/workspace.tar.gz ~/work/workspace.tar.gz