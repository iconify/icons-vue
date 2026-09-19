<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v_htsv5cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pushbullet" /></template>
<style>
.v_htsv5cf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.5 8.409h5.495a1 1 0 0 1 1 1v29.273a1 1 0 0 1-1 1H6.5a2 2 0 0 1-2-2V10.408a2 2 0 0 1 2-2m12.636-.09h11.743c16.828.033 16.828 31.337 0 31.274H19.136a1 1 0 0 1-1-1V9.317a1 1 0 0 1 1-1");
}

</style>
