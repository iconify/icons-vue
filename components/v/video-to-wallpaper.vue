<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qhi71r0it"/><circle class="e619ombtz"/><circle class="u0l5m4vyz"/><circle class="rb8sxnb0b"/><circle class="w9qz2pbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:video-to-wallpaper" /></template>
<style>
.e619ombtz {
  cx: 23.894px;
  cy: 16.146px;
  r: 7.448px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qhi71r0it {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.29 22.24h-5.282m-7.854 0h-.677v14.895h24.917V22.24h-2.031m6.77 11.781l8.667 5.281V19.938l-8.667 5.281h-4.739v8.802z");
}

.rb8sxnb0b {
  cx: 23.894px;
  cy: 16.146px;
  r: 2.844px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u0l5m4vyz {
  cx: 9.946px;
  cy: 18.719px;
  r: 5.146px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.w9qz2pbok {
  cx: 9.946px;
  cy: 18.719px;
  r: 1.76px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
