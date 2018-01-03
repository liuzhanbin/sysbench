yum install automake libtool mysql-server mysql-devel mysql-libs make -y

./configure --prefix=/usr/local/sysbench/ --with-mysql-includes=/usr/include/mysql/ --with-mysql-libs=/usr/lib64/mysql/ --with-mysql

make && make install
