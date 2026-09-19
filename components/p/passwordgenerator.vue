<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="tp1imxchh"/><path class="pyo7hiv5e"/><path class="spi0_pasc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:passwordgenerator" /></template>
<style>
.pyo7hiv5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.4 20.4a11.47 11.47 0 0 1 5.2-13.3a11.31 11.31 0 0 1 14.1 2.3a11.32 11.32 0 0 1-13 17.9");
}

.spi0_pasc {
  fill: none;
  stroke: currentColor;
  d: path("M20.4 20.4L5.5 37v5.4h6.1l.7-4.2l6.5-.4l.5-5.5l5.5-.1l1.8-4.8");
}

.tp1imxchh {
  cx: 33.4px;
  cy: 14.8px;
  r: 3.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
