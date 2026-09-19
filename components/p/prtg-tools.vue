<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tv7yyyb6t"/><path class="g-vlz12ml"/><circle class="trykrmsqb"/><path class="chrxouodv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:prtg-tools" /></template>
<style>
.chrxouodv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.357 36.643l-2.642 2.642m3.688-6.546l-1.65 1.65l.604 2.254l2.254.604l1.65-1.65");
}

.g-vlz12ml {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.364 22.075l16.991 9.589l-2.86 2.579z");
}

.trykrmsqb {
  cx: 36.5px;
  cy: 36.5px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tv7yyyb6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.633 29.754q.017-.345.017-.694c0-7.61-6.16-13.77-13.76-13.77c-7.61 0-13.77 6.16-13.77 13.77c0 3.03.98 5.84 2.64 8.11L7.7 39.23a19.4 19.4 0 0 1-3.57-11.24c0-10.78 8.74-19.53 19.53-19.53c10.78 0 19.53 8.75 19.53 19.53a19.6 19.6 0 0 1-.642 4.984m-5.159-18.868l-5.726 6.388m-21.579-6.54l3.082 3.702");
}

</style>
