<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="kets-x7wy"/><circle class="dkq3jfbum"/><path class="hqzqmicng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:play-deals" /></template>
<style>
.dkq3jfbum {
  cx: 13.015px;
  cy: 12.471px;
  r: 5.818px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hqzqmicng {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.697 41.151a4.113 4.113 0 0 0 5.803.003l28.79-28.52a4.08 4.08 0 0 0 .028-5.772l-.014-.014a4.114 4.114 0 0 0-5.803-.003c-9.039 8.97-19.745 19.557-28.79 28.52a4.08 4.08 0 0 0-.014 5.786");
}

.kets-x7wy {
  cx: 34.796px;
  cy: 35.969px;
  r: 5.818px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
