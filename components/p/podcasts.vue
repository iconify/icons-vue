<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="t1mfal-np"/><path class="jna51ob5o"/><path class="s54c1fvpd"/><path class="zhaxeio6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:podcasts" /></template>
<style>
.jna51ob5o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.5 37a5.5 5.5 0 1 0-11 0v3a5.5 5.5 0 1 0 11 0z");
}

.s54c1fvpd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.2 39.2c3.89-3.89 6.3-9.26 6.3-15.2c0-11.87-9.63-21.5-21.5-21.5S2.5 12.13 2.5 24c0 5.94 2.41 11.31 6.3 15.2");
}

.t1mfal-np {
  cx: 24px;
  cy: 24px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zhaxeio6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.55 33.55c2.44-2.45 3.95-5.82 3.95-9.55c0-7.46-6.04-13.5-13.5-13.5S10.5 16.54 10.5 24c0 3.73 1.51 7.1 3.95 9.55");
}

</style>
