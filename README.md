# mis4
权限查询作业</br>
查询用户test1可以查看的页面（Sys_menu）</br>
<p>根据用户名test1在user表中查询UserID,根据查询到的USERID在表USERROLE中查询RoleID,然后根据查询到的RoleID以及sys_menu,在CF-privilge表中查询得到privilgeID,最后得到menuname。</p>

订单(order)页面中的操作权限<br>
<p>在上一个查询用户test1可以查看页面的基础上，查询Sys_Menu表中订单对应的MenuNo,然后跟据查询得到的MenuNo,查询Sys_Botton表中MenuNo对应的操作权限。</p>
