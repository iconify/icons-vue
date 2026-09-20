<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="vj_3q0bho"/><path class="vtyt5wugk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mapsgo" /></template>
<style>
.vj_3q0bho {
  cx: 24px;
  cy: 17.93px;
  r: 4.82px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vtyt5wugk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.83c.43 0 1.26-.11 1.26-1.74c0-5.14 7.27-10.78 10.57-17.15a13.76 13.76 0 1 0-23.66 0c3.3 6.37 10.57 12 10.57 17.15c0 1.63.83 1.74 1.26 1.74");
}

</style>
