<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5fns8rsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-cam-wall-mount-outline" /></template>
<style>
.m5fns8rsk {
  fill: currentColor;
  d: path("M3.953 15.822q-.472-.475-.472-1.142V8.215q0-.667.475-1.139q.476-.472 1.144-.472t1.14.475t.472 1.146q.702-1.26 1.966-2.017Q9.942 5.45 11.5 5.45q1.103 0 2.11.42t1.779 1.192l3.877 3.877q.242.243.363.538q.121.294.121.598t-.121.598t-.364.539l-5.484 5.504q-.222.22-.515.339t-.616.12t-.628-.12q-.304-.12-.528-.34L7.611 14.84q-.275-.276-.497-.56t-.403-.604v1.006q0 .666-.475 1.14q-.476.475-1.143.475t-1.14-.474M7 10.925q0 .9.338 1.725t.987 1.475l3.883 3.883q.192.192.452.192t.432-.192l5.466-5.49q.173-.193.173-.453t-.173-.432L14.675 7.75q-.65-.65-1.463-.987T11.5 6.425q-1.875 0-3.187 1.313T7 10.925m5.904 1.429");
}

</style>
