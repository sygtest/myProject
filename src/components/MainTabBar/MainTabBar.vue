<template>
      <tab-bar>
      <tab-bar-item path="/home">
        <img src="~assets/img/tabbar/home.svg" slot="item-icon">
        <img src="~assets/img/tabbar/home_active.svg" slot="item-icon-active">
        <div slot="item-name">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category">
        <img src="~assets/img/tabbar/category.svg" slot="item-icon">
        <img src="~assets/img/tabbar/category_active.svg" slot="item-icon-active">
        <div slot="item-name">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart">
        <img src="~assets/img/tabbar/shopcart.svg" slot="item-icon">
        <img src="~assets/img/tabbar/shopcart_active.svg" slot="item-icon-active">
        <div slot="item-name">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile">
        <img src="~assets/img/tabbar/profile.svg" slot="item-icon">
        <img src="~assets/img/tabbar/profile_active.svg" slot="item-icon-active">
        <div slot="item-name">我的</div>
      </tab-bar-item>
    </tab-bar>
</template>  


<script>
  import TabBar from 'components/tabbar/TabBar'
  import TabBarItem from 'components/tabbar/TabBarItem'

  export default {
    name: "MainTabBar",
    components: {
      TabBar,
      TabBarItem
    }
  }

</script>

<style scoped>

</style>