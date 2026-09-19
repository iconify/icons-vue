<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="fvl_8plug"/><circle class="ny0negbmt"/><path class="jn72-bmtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nintendo-switch-online" /></template>
<style>
.fvl_8plug {
  cx: 13.5px;
  cy: 16.2px;
  r: 3.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jn72-bmtb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.5 5.5h-7.3c-4.8 0-8.7 3.9-8.7 8.6V34c0 4.7 3.9 8.6 8.7 8.6h7.3zm12.3 0h-7.3v37.1h7.3c4.8 0 8.7-3.9 8.7-8.6V14.1c0-4.7-3.9-8.6-8.7-8.6");
}

.ny0negbmt {
  cx: 34.5px;
  cy: 26.2px;
  r: 3.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
