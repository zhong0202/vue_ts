<!--
 * @Author: zhongao 1417512076@qq.com
 * @Date: 2022-06-11 21:16:51
 * @LastEditors: zhongao 1417512076@qq.com
 * @LastEditTime: 2022-06-15 07:50:50
 * @FilePath: \vue_ts\src\App.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<template>
  <div id="app">
    <div>{{ a }}</div>
    <router-view />
  </div>
</template>
<script lang='ts'>
import Vue from 'vue'
import Component from 'vue-class-component'
@Component
export default class App extends Vue {
  a = 1
  b = 3
  test () {
    console.log(this.a.c)
  }
}
</script>
<style lang="scss" scoped></style>
