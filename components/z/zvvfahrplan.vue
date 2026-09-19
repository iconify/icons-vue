<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aeyym_byd"/><circle class="l43864bee"/><circle class="ceoja1f8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zvvfahrplan" /></template>
<style>
.aeyym_byd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.39 23.85v-6.24h-6.24m6.24 0L17.61 30.39");
}

.ceoja1f8a {
  cx: 38.34px;
  cy: 9.66px;
  r: 4.16px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l43864bee {
  cx: 9.66px;
  cy: 38.34px;
  r: 4.16px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
