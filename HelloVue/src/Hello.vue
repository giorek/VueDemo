<template>
   <div class="hello">
     <h1 >{{msg}}
      <a href="http://www.baidu.com" target="_blank">jump</a>
     </h1>
   </div>
</template>

<script>export default {name: 'hello',
  data: function () {
    return {msg: '点击后方链接进行跳转：'}
  }
}
</script>
