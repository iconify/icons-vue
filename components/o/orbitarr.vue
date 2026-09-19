<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n08f7nw0g"/><circle class="qchoqwbmr"/><circle class="bahioci-r"/><circle class="j5j-km3hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:orbitarr" /></template>
<style>
.bahioci-r {
  cx: 8.716px;
  cy: 39.283px;
  r: 4.216px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j5j-km3hm {
  cx: 24px;
  cy: 24px;
  r: 12.121px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n08f7nw0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.372 32.337A19.5 19.5 0 0 1 4.5 24C4.5 13.23 13.23 4.5 24 4.5c2.883 0 5.73.64 8.337 1.872m9.29 9.29A19.5 19.5 0 0 1 43.5 24c0 10.77-8.73 19.5-19.5 19.5a19.5 19.5 0 0 1-8.337-1.872");
}

.qchoqwbmr {
  cx: 39.284px;
  cy: 8.716px;
  r: 4.216px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
