<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="qlphrtb3g"/><path class="jdx-1nb-d"/><circle class="uioqj1baw"/><path class="d00_nx35t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:privacium" /></template>
<style>
.d00_nx35t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.643 22.158h10.714c.407 0 .736.33.736.736v7.919c0 .406-.33.735-.736.735H18.643a.736.736 0 0 1-.735-.735v-7.92c0-.406.33-.735.735-.735m1.324 0v-1.69a4.03 4.03 0 0 1 8.06 0v1.69");
}

.jdx-1nb-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.108 24H44.5m-41 0h5.392");
}

.qlphrtb3g {
  cx: 24px;
  cy: 24px;
  r: 15.108px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uioqj1baw {
  cx: 23.997px;
  cy: 26.853px;
  r: 2.028px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

</style>
