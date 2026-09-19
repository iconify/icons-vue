<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-45 24 24)" class="o67caib-r"/><path class="mi5u3mg4v"/><path class="k4rmolb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:palmpay" /></template>
<style>
.k4rmolb8s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.565 29.88l17.44-17.441a1.263 1.263 0 0 1 1.766-.021l7.432 7.089m10.245-.897L25.007 36.051a1.263 1.263 0 0 1-1.766.021l-7.431-7.088");
}

.mi5u3mg4v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.157 4.262a5.69 5.69 0 0 1 5.685 0l12.83 7.407a5.69 5.69 0 0 1 2.843 4.924v14.814a5.69 5.69 0 0 1-2.843 4.924l-12.83 7.407a5.69 5.69 0 0 1-5.685 0l-12.83-7.407a5.69 5.69 0 0 1-2.842-4.924V16.593a5.69 5.69 0 0 1 2.842-4.924z");
}

.o67caib-r {
  width: 5.053px;
  height: 5.053px;
  x: 21.473px;
  y: 21.473px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.632px;
  ry: 0.632px;
}

</style>
