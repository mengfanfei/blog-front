<template>
  <div>
    <div class="navbar">
      <div class="navbar-center">
        <div class="header-left">
          <span class="header-logo"><a href="/">前端小孟</a></span>
          <span class="header-txt">积累前端知识，准备逆袭</span>
        </div>
        <div class="header-right">
          <span class="right-item"><a style="color: #999;" href="/">首页</a></span>
          <span class="right-item"><a style="color: #999;" href="/">生活圈</a></span>
        </div>
      </div>
    </div>
    <div style="height: 50px;"></div>
  </div>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style>
  .navbar {
    position: fixed;
    background: #ffffff;
    border-bottom: 1px solid #eee;
    height: 50px;
    width: 100vw;
    box-sizing: border-box;
    overflow: hidden;
    padding: 5px;
  }
  .navbar-center {
    height: 100%;
    max-width: 1100px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-flow: row wrap;
    box-sizing: border-box;
  }
  .header-logo {
    color: #1e90ff;
    font-size: 24px;
    text-align: left;
  }
  .header-txt {
    font-size: 10px;
    color: #999999;
    display: inline-block;
    padding-left: 6px;
  }
  .header-right {
    height: 40px;
    line-height: 40px;
    box-sizing: border-box;
  }
  .right-item {
    display: inline-block;
    color: #999999;
    padding: 0 20px;
    font-size: 15px;
  }
</style>