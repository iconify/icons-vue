<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="e46-p5zaq"/><rect class="iiz0q5bgk"/><path class="ffy50bczd"/><rect class="ve7lg4izc"/><path class="jtm1p5b-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:space-station" /></template>
<style>
.e46-p5zaq {
  width: 4.5px;
  height: 9.5px;
  x: 2.75px;
  y: 7.25px;
  rx: 1px;
}

.ffy50bczd {
  d: path("M2.75 12h4.5m9.5 0h4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iiz0q5bgk {
  width: 4.5px;
  height: 9.5px;
  x: 16.75px;
  y: 7.25px;
  rx: 1px;
}

.jtm1p5b-g {
  d: path("M7.25 12h2.5m4.5 0h2.5M12 8.25v-4m0 11.5v4");
}

.ve7lg4izc {
  width: 4.5px;
  height: 7.5px;
  x: 9.75px;
  y: 8.25px;
  rx: 1.5px;
}

</style>
