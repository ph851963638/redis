# redis

get nums 
incr nums  ++i
decr  nums  --i
append goods_name 123
incr by  decr by  自增  自减
set u_01 
hgetall 
hset myhash username  wanghai 

hget myhash username  jack 

hset myhash username lisi
// 建立一个集合
hmset myhash2 username lisi age 20
取值hget  myhash username 

//取多个字段的值
hmget myhash2 username age

//取所有field-value
hgetall myhash2

删除命令hdel key field 
hdel myhash username
删除整个
del key 
del myhash2
