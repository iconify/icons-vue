<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sxt2fdznr"/><path class="m_vx_lb4m"/><path class="osia6ybbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yomoni" /></template>
<style>
.m_vx_lb4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.844 5.6l11.154 18.37L35.285 5.54");
}

.osia6ybbz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.638 5.559l8.32 13.66l8.247-13.466m9.12-.217L18.972 42.5");
}

.sxt2fdznr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.674 5.5l15.944 26.055l-6.376 10.789m3.195-10.524l-5.786 9.486m2.732-9.982l-5.05 8.205M9.917 5.57L24.05 28.492l14.475-22.9");
}

</style>
