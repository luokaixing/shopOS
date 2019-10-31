<!-- leftNav -->
<template>
  <div class="left-nav">
    <ul>
      <li>
        <img src="@/assets/shouyinzhongxin.png" alt />
        <div>收银</div>
      </li>
      <li>
        <img src="@/assets/shangcheng.png" alt />
        <div>店铺</div>
      </li>
      <li>
        <img src="@/assets/hanbao.png" alt />
        <div>商品</div>
      </li>
      <li>
        <img src="@/assets/huiyuanqia.png" alt />
        <div>会员</div>
      </li>
      <li>
        <img src="@/assets/tongji.png" alt />
        <div>统计</div>
      </li>
      <li>
        <img src="@/assets/ziyuan.png" alt />
        <div>设置</div>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'leftNav',
  data () {
    return {}
  }
}
</script>

<style>
.left-nav {
  color: #fff;
  font-size: 10px;
  height: 100%;
  background-color: #1d8ce0;
  float: left;
  width: 5%;
}
.left-nav ul {
  margin: 0;
  padding: 0;
}
.left-nav li {
  list-style: none;
  text-align: center;
  border-bottom: 1px solid #20a0ff;
  padding: 10px;
}
</style>
