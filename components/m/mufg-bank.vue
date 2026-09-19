<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ol7d0nbeq"/><circle class="eezkri9di"/><circle class="i7wdi9_uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mufg-bank" /></template>
<style>
.eezkri9di {
  cx: 24px;
  cy: 24px;
  r: 5.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i7wdi9_uf {
  cx: 24px;
  cy: 24px;
  r: 12px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ol7d0nbeq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18 10.5c-7.456 0-13.5 6.044-13.5 13.5S10.544 37.5 18 37.5a13.5 13.5 0 0 0 6-1.435a13.5 13.5 0 0 0 6 1.435c7.456 0 13.5-6.044 13.5-13.5S37.456 10.5 30 10.5a13.5 13.5 0 0 0-5.978 1.422A13.5 13.5 0 0 0 18 10.5");
}

</style>
