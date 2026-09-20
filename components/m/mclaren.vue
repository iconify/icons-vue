<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hxjd-kvtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mclaren" /></template>
<style>
.hxjd-kvtj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 24.817C37.16 7.22 62.037 9.58 25.155 34.6c2.963-3.163 5.443-7.633 2.611-10.778c-2.322-3.185-13.1-3.138-23.266.996Z");
}

</style>
