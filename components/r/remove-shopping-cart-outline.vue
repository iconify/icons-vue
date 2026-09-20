<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opjuteb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:remove-shopping-cart-outline" /></template>
<style>
.opjuteb_h {
  fill: currentColor;
  d: path("M9.5 7.5v-1h5v1zM6.241 20.682q-.433-.434-.433-1.066t.433-1.067q.434-.433 1.067-.433t1.066.433t.434 1.067t-.434 1.066t-1.066.434t-1.067-.434m9.385 0q-.434-.434-.434-1.066t.434-1.067q.434-.433 1.066-.433t1.067.433q.433.434.433 1.067q0 .632-.433 1.066q-.434.434-1.067.434t-1.066-.434M2 3.5v-1h2.448l4.096 8.616h6.635q.173 0 .308-.087q.134-.087.23-.24L19.213 4.5h1.14l-3.784 6.835q-.217.365-.564.573t-.763.208H8.1l-1.215 2.23q-.154.231-.01.5t.433.27h10.884v1H7.308q-.875 0-1.309-.735t-.018-1.485l1.504-2.68L3.808 3.5z");
}

</style>
