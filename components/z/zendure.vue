<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="y5qz-9bil"/><circle class="pw0t8tbiq"/><path class="uhe7d768d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zendure" /></template>
<style>
.pw0t8tbiq {
  cx: 14.243px;
  cy: 24px;
  r: 9.743px;
  fill: none;
  stroke: currentColor;
}

.uhe7d768d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.428 24h5.629m-2.814-2.815v5.63M31.07 24h5.629");
}

.y5qz-9bil {
  cx: 33.757px;
  cy: 24px;
  r: 9.743px;
  fill: none;
  stroke: currentColor;
}

</style>
