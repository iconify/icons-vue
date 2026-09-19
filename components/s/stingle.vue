<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="px1y43e7h"/><path class="rllacm4ei"/><path class="jktp2ybaf"/><path class="m930xbc_z"/><path class="e51oimb1k"/><path class="ftfytsx5r"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stingle" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e51oimb1k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.146 19.17s9.674-14.108 30.15-8.208");
}

.ftfytsx5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.023 21.202v-5.008s-.44-2.273-5.865-2.273s-5.845 2.088-5.845 2.088v4.91l11.797 4.257v3.86l-6.043 6.044l-5.74-5.74v-3.48");
}

.jktp2ybaf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.837 40.259S21.652 45.798 8.752 28.836");
}

.m930xbc_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.941 42.278S2.544 28.693 14.525 11.071");
}

.px1y43e7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.949 2.679s16.443 4.719 17.317 26.01");
}

.rllacm4ei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.555 15.344s.687 17.094-19.252 24.613");
}

</style>
