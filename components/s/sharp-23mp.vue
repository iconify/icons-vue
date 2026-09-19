<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bj1f5fbpw"/><path class="k4n51fjcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-23mp" /></template>
<style>
.bj1f5fbpw {
  fill: currentColor;
  d: path("M3 3v18h18V3zm3.5 5h3V7h-3V5.5H11V9H8v1h3v1.5H6.5zm6 10.5H11V14h-1v3H8.5v-3h-1v4.5H6v-6h6.5zM13 10h3V9h-2V8h2V7h-3V5.5h4.5v6H13zm5 7h-3v1.5h-1.5v-6H18z");
}

.k4n51fjcs {
  fill: currentColor;
  d: path("M15 14h1.5v1.5H15z");
}

</style>
