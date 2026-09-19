<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w445ytk8a"/><path class="awrvxmwwv"/><circle class="nklefk4du"/><circle class="el7fucahe"/><circle class="himdm0sxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:weawow" /></template>
<style>
.awrvxmwwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.47 22.79l-1.65 5.3l-1.65-5.3l-1.65 5.3l-1.65-5.3m-11.74 0l-1.65 5.3l-1.65-5.3l-1.65 5.3l-1.65-5.3");
}

.el7fucahe {
  cx: 21.62px;
  cy: 18.12px;
  r: 0.75px;
  fill: currentColor;
}

.himdm0sxv {
  cx: 24px;
  cy: 24.09px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nklefk4du {
  cx: 26.38px;
  cy: 18.12px;
  r: 0.75px;
  fill: currentColor;
}

.w445ytk8a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.61 26.64a12.31 12.31 0 0 0-4.32-9.37v0a7.68 7.68 0 0 0-9.91-7.38A10.86 10.86 0 0 0 9.14 22.05a12.41 12.41 0 0 0 10.68 18.77h19.45l-6.37-2.75a12.34 12.34 0 0 0 7.71-11.43");
}

</style>
