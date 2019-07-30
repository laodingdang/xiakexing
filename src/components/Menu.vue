<template>
  <div class="menu">
    <div class="h1">开始游戏</div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="less" scoped>
.menu {
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  .h1 {
    font-size: 56px;
    text-align: center;
    height: 80px;
    padding: 24px;
  }
  .h1:hover {
    color: #fff;
    background: rgba(0, 0, 0, 0.8)
  }
}
</style>
