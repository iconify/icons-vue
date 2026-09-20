<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nec760bny"/><path class="djqu_1b-p"/><rect transform="matrix(-1 0 0 -1 68.246 59.599)" class="skcp_6bwj"/><path class="uhh00nbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tata-1mg" /></template>
<style>
.djqu_1b-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37 25.988v8.63a2.877 2.877 0 0 1-2.877 2.877a2.87 2.87 0 0 1-2.034-.843");
}

.nec760bny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4M11 23.67l2.877-1.566m0 0v11.507M11 10.505h6.549m-3.274 7.715v-7.715");
}

.skcp_6bwj {
  width: 5.754px;
  height: 7.624px;
  x: 31.246px;
  y: 25.988px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.877px;
  ry: 2.877px;
}

.uhh00nbkz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.862 28.864a2.877 2.877 0 0 1 5.754 0v4.747m-5.754-7.623v7.623m5.754-4.747a2.877 2.877 0 0 1 5.754 0v4.747M17.549 18.197l3.212-7.692m3.214 7.715l-3.214-7.715m3.264 0h6.549m-3.275 7.715v-7.715m3.275 7.692l3.211-7.692M37 18.22l-3.215-7.715M16.681 22.104H37m-8.631 15.391H13.877");
}

</style>
