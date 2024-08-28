**Error**
/home/jiangyuancheng/works/geods/cmake-build-debug/src/testApps/testApp: /lib/x86_64-linux-gnu/libstdc++.so.6: version `GLIBCXX_3.4.32' not found (required by /home/jiangyuancheng/works/geods/cmake-build-debug/src/testApps/testApp)
/home/jiangyuancheng/works/geods/cmake-build-debug/src/testApps/testApp: /lib/x86_64-linux-gnu/libstdc++.so.6: version `GLIBCXX_3.4.31' not found (required by /home/jiangyuancheng/works/geods/cmake-build-debug/src/testApps/testApp)
Solution:
cd /lib/x86_64-linux-gnu/
sudo ln -s libstdc++.so.6 /usr/local/gcc-14/lib64/libstdc++.so.6
