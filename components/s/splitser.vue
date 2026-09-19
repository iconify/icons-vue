<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k801ecave"/><path class="i04j9dkpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:splitser" /></template>
<style>
.i04j9dkpc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.57 26.26a3.65 3.65 0 0 1 5.16-5.17l7.47 7.47a3.65 3.65 0 1 1-5.2 5.16Z");
}

.k801ecave {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.75 34.6a3.66 3.66 0 0 1-2.58-1.06l-7.46-7.47a3.65 3.65 0 0 1 5.16-5.16l4.88 4.88l11.52-11.51a3.65 3.65 0 1 1 5.16 5.16l-14.09 14.1a3.66 3.66 0 0 1-2.59 1.06");
}

</style>
