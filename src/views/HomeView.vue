<template>
  <div class="home">
    <div class="card-list">
      <div class="card-item"></div>
      <div class="card-item"></div>
      <div class="card-item"></div>
    </div>
    <van-button type="primary">默认按钮</van-button>
  </div>
</template>

<script>
import { Button } from "vant";

export default {
  components: {
    "van-button": Button,
  },
};
</script>
<style lang="less">
.card-item {
  display: inline-block;
  width: (375px /2);
  height: 20px;
  vertical-align: top;
  margin-bottom: 10px;
  background: #f1f1f1;
  font-size: 14px;
}
</style>
