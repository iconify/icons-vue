<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk9shrbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:production-quantity-limits-outline-rounded" /></template>
<style>
.vk9shrbgw {
  fill: currentColor;
  d: path("M6.241 20.682q-.433-.434-.433-1.066t.433-1.067q.434-.433 1.067-.433t1.066.433t.434 1.067t-.434 1.066t-1.066.434t-1.067-.434m9.385 0q-.434-.434-.434-1.066t.434-1.067q.434-.433 1.066-.433t1.067.433q.433.434.433 1.067q0 .632-.433 1.066q-.434.434-1.067.434t-1.066-.434M3.808 3.5H2.5q-.213 0-.357-.143T2 3t.143-.357T2.5 2.5h1.439q.236 0 .428.121q.193.121.299.338l3.878 8.157h6.635q.173 0 .308-.087q.134-.087.23-.24l3.356-6.039q.068-.115.177-.183t.25-.067q.287 0 .43.247t.003.497l-3.364 6.09q-.217.366-.564.574t-.763.208H8.1l-1.215 2.23q-.154.231-.01.5t.433.27h10.384q.214 0 .357.143t.143.357t-.143.356t-.357.144H7.308q-.875 0-1.309-.735t-.018-1.485l1.504-2.68zm7.758 5.818q-.182-.182-.182-.434q0-.251.182-.433T12 8.269t.434.182t.182.433t-.182.434T12 9.5t-.434-.182m.077-2.961Q11.5 6.213 11.5 6V2q0-.213.143-.357T12 1.5t.357.143T12.5 2v4q0 .214-.143.357T12 6.5t-.357-.143");
}

</style>
