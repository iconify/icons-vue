<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h64tiwbkb"/><circle class="k8pn9ebyy"/><path class="rug6oqp7n"/><circle class="d3agvjbzf"/><circle class="ibknurrde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:skymap" /></template>
<style>
.d3agvjbzf {
  cx: 7.258px;
  cy: 32.667px;
  r: 2.758px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h64tiwbkb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.864 30.303L43.5 40.939");
}

.ibknurrde {
  cx: 37.722px;
  cy: 9.424px;
  r: 2.364px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k8pn9ebyy {
  cx: 23.54px;
  cy: 20.98px;
  r: 12.869px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rug6oqp7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.41 13.823l2.363 4.727l5.252.788l-3.808 3.677l.92 5.121l-4.597-2.494l-4.596 2.494l.92-5.12l-3.809-3.678l5.253-.788l2.1-4.727Z");
}

</style>
