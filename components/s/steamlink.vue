<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xoitq4u1g"/><circle class="vk9ywmb8l"/><circle class="obsladowy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:steamlink" /></template>
<style>
.obsladowy {
  cx: 34.35px;
  cy: 18.84px;
  r: 4.11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vk9ywmb8l {
  cx: 13.65px;
  cy: 18.84px;
  r: 4.11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xoitq4u1g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.59 18za7.28 7.28 0 0 0-12.24-4.34H18.67a7.3 7.3 0 0 0-5-2A7.3 7.3 0 0 0 6.42 18L4.51 33.24c-.32 3.89 6.53 4 7.81 1.32l3.09-4.9a4.32 4.32 0 0 1 3.59-2.3h10a4.24 4.24 0 0 1 3.62 2.3l3.09 4.9c1.28 2.66 8.13 2.57 7.81-1.32Z");
}

</style>
