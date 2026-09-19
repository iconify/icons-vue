<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="it11wruyt"/><circle class="mzh4ytbvf"/><path class="tn1-pcmbx"/><circle class="mnalqditp"/><circle class="zrietqb-d"/><path class="iuchl92jm"/><path class="o5zj_2q6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:skymap" /></template>
<style>
.it11wruyt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.4 5.6a47.15 47.15 0 0 1-32.9 0c-1-.4-2.3.9-2 2c3.2 10.8 3.7 21.7 0 32.9c-.3 1 1 2.4 2 2c10.6-4.6 21.4-5.5 32.9 0c1 .5 2.3-.9 2-2c-2.4-9.6-4.3-19.2 0-32.9a1.65 1.65 0 0 0-2-2m-9.3 25.5l8.1 8.1M23.7 8.9v5.2m0 19.9v4.4");
}

.iuchl92jm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 7.6a69.4 69.4 0 0 1 2.3 10.8m.1 11.2a49.4 49.4 0 0 1-2.3 10.5M34.5 7.6a59.5 59.5 0 0 0-2.3 10.8M32 29.8A53 53 0 0 0 34.2 40");
}

.mnalqditp {
  cx: 11.6px;
  cy: 32.9px;
  r: 2.1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mzh4ytbvf {
  cx: 24px;
  cy: 24px;
  r: 9.8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o5zj_2q6c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.6 13.3c-1.4.4-2.8.8-4.2 1.1m-3.5.7c-1.2.2-2.3.3-3.5.5m-10.7 0a53.2 53.2 0 0 1-11.6-2.4m33.7 21.2a62 62 0 0 0-11.2-2.3M18.2 32c-1.5.1-3.1.4-4.6.6m-4.1 1a19 19 0 0 0-2.2.7m32.3-10.6h-5.8m-19.8 0H8.3");
}

.tn1-pcmbx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.7 16.7l1.8 3.6l4 .6l-2.9 2.8l.7 3.9l-3.5-1.9l-3.5 1.9l.7-3.9l-2.9-2.8l4-.6ZM11.5 7.1l.3 1.6l1.5.7l-1.4.8l-.2 1.7l-1.2-1.1l-1.6.4l.7-1.5l-.9-1.5l1.7.2Z");
}

.zrietqb-d {
  cx: 34.8px;
  cy: 15.2px;
  r: 1.8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
