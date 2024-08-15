# mysqlshutdownunexpectdly
my mysql getting shut down unexpectdly. how to resolve this issue

Step-1) sabse pahle jo data ke name se folder hai usko change kar denge data_old ke name se. aur ek new folder bana lenge data ke name se
Step-2) jo bhi backup folder me data hai waha se copy kar lenge sara chiz aur isme apne data folder me paste kar denge
Step-3) jo humara data_old folder hai usme se database folder ka naam ko copy kar lenge aur ibdata1 file ko copy kar lenge kyuki sara database ka details isi file ke andar rahta hai except mysql, performance_schema, and phpmyadmin from data_old folder and paste it in the data folder. 
