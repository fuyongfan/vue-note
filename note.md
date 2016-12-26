## 声明式渲染  
```
{{message}}
```
## 条件与循环
- v-if = 'false' 标签   display : none          
- v-for = 'name in names' 将 v-for 挂载在子节点    
eg. right     
```
<ul id = 'app'>
    <li v-for = 'name in names'>{{name.title}}</li>
</ul>
```      
eg. wrong     
```
<ul id = 'app' v-for = 'name in names'>
    <li>{{name.title}}</li>
</ul>
```  
