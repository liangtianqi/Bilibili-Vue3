/* eslint-disable */
<template>
 <!--  <h1>Bilibili 主页</h1>
  <router-link to="/video/1">点我去视频详情页</router-link> -->
  <!-- 头部组件 -->
  <AppHeader/>
  <HomeChannel/>
  <HomeSwipe/>
  <HomeVideoList/>
  
</template>

<script setup lang = "ts">
import AppHeader from '@/components/app-header.vue'
import HomeChannel from './components/home-channel.vue'
import HomeSwipe from './components/home-swipe.vue'
import HomeVideoList from './components/home-video-list.vue';

</script>