Vue
Vue是一套用于构建用户界面的渐进式框架.与其它大型框架不同的是。Vne 被设计为可以自底向上逐层应用，Vue的核心库只关注视图层.不仅易于上手，还便于与第三方库有项目整合.另一方面，当与现代化的工具链以及各种支持类库结合使用.

###v-cloak
v-cioak:能够解决插值表达式的闪烁问题

###v-text
使用v-text 是没有闪炼问题的. 
v-tet 会覆盖元素元素中原本的内容，但是，差值表达式只会替换自己的这个占位符，不会把整个元素的内容清空。

###v-bind
V一bind是vue提供的用于绑定属性的指令。
注意：v-bmd 指令可以被简写为“:”英文冒号。
v-bind 中可以写合法的JS表达式
v-bind只能实现单项数据绑定 无法实现数据的双向数据绑定。

###v-on
vue中提供了 v-on 事件绑定机制  缩写是 @ 


methods 这个methods属性中定义了当前vue实例所有可用的方法
mouseover  鼠标移动上触发

###v-model 
v-model：实现双向的数据绑定。
使用v-model指令，可以实现表单元素和model中数据的双向便绑定。
v-model只能运用在表单元素中（input、select、checkbox、text、tarea）

###v-if
v-if的特点：每次都会重新删除或创建元素。
v-if有较高的切换切换性能消耗，如果元素涉及到频繁的切换，最好不要用v-if。

###v-show
v-show的特点：每次不会重新进行dom的删除和创建操作，只是切换了元素。
display：none；样式
v-show：有较高的初始渲染消耗 如果元素可能永远不会被显示出来被用户看到，则推荐使用v-if。

###事件修饰符
.stop 阻止冒泡
.prevent 阻止默认行为的
.capture 捕获行为 
.self 自己身上执行
.once 只执行一次

###属性
el 指定要控制的区域
data 对象 指定控制的区域内要用到的数据。
methods  对象 定义了一些方法 可以自定义。

在vm实例中如果要访问data上的数据或者要访问methods中的方法必须带this

在v-for中要会使用key属性，（只接受string/number）


在vue中绑定样式的两种方式  v-bind:class   v-bind:style；
