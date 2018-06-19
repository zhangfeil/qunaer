<template>
    <div>
      <div class="header">
        <div class="left">
          <span class="iconfont">&#xe697;</span>
          </div>
        <div class="input-box">
          <span class="iconfont">&#xe6ac;</span>
          <input type="text" placeholder="请输入要搜索的地区">
        </div>
        <div class="right"><span class="city">城市</span></div>
      </div>
    </div>
</template>

<script>
    export default {

    }
</script>

<style lang="stylus" scoped>
/*<style lang="stylus">使用stylus语法*/
/*引入styl文件*/
@import "~styles/varibles.styl"
  .header
    display:flex
    flex-direction:row
    align-items:center
    height:0.86rem
    background:$bgColor
    font-size:15px
    .input-box
      flex:1
      background:#ffffff
      display:flex
      flex-direction:row
      height:0.6rem
      align-items:center
      border-radius:5px
      span
        margin-left:20px
        margin-right:10px
      input
        border:none
        outline:none
        height:100%

    .left
      width:0.7rem
      text-align:center
      line-height:0.86rem
      font-size:30px
      span
        font-size:.5rem
    .right
      width:1.2rem
      text-align:center
      .city
        position:relative
      .city:after
        content:''
        display:block
        position:absolute
        bottom:0
        right:-10px
        border:5px solid
        border-color:white transparent transparent transparent;

</style>
