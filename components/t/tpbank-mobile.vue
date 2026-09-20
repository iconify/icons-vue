<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zn9ie7l8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tpbank-mobile" /></template>
<style>
.zn9ie7l8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.35 39.61l-3.836-27.054M5.58 10.563a2.333 2.333 0 0 1 1.65-2.857M25.65 39.61a2.333 2.333 0 0 1-3.3 0M40.77 7.706a2.333 2.333 0 0 1 1.65 2.857M25.65 39.61l16.77-29.046m-1.65-2.858H7.23m-1.65 2.857L22.35 39.61M7.23 7.706L32.859 18.44m9.561-7.877L20.802 28.689");
}

</style>
