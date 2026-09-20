<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4yg0fs1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-cam-wall-mount" /></template>
<style>
.x4yg0fs1n {
  fill: currentColor;
  d: path("M3.953 15.822q-.472-.475-.472-1.142V8.215q0-.667.475-1.139q.476-.472 1.144-.472t1.14.475t.472 1.146q.702-1.26 1.966-2.017Q9.942 5.45 11.5 5.45q1.103 0 2.11.42t1.779 1.192l3.877 3.877q.242.243.363.538q.121.294.121.598t-.121.598t-.364.539l-5.484 5.504q-.222.22-.515.339t-.616.12t-.628-.12q-.304-.12-.528-.34L7.611 14.84q-.275-.276-.497-.56t-.403-.604v1.006q0 .666-.475 1.14q-.476.475-1.143.475t-1.14-.474");
}

</style>
