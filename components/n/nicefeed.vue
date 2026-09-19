<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle transform="rotate(-.073 11.382 22.014)" class="lpklpmtoz"/><circle class="d-vwdp5sy"/><path class="jgz6igeoh"/><path class="kss1_lbnu"/><path class="a00my8svj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nicefeed" /></template>
<style>
.a00my8svj {
  fill: none;
  stroke: currentColor;
  d: path("M37.387 11.37H42.5M11.371 37.387V42.5");
}

.d-vwdp5sy {
  cx: 22.277px;
  cy: 11.371px;
  r: 5.871px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jgz6igeoh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.387 11.37A26.016 26.016 0 0 1 11.37 37.387");
}

.kss1_lbnu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 11.37A31.13 31.13 0 0 1 11.371 42.5");
}

.lpklpmtoz {
  cx: 11.371px;
  cy: 21.99px;
  r: 5.871px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
