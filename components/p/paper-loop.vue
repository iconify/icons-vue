<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c0ilkxbne"/><rect class="rqjs0ub5j"/><path class="kq4yk7byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paper-loop" /></template>
<style>
.c0ilkxbne {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.475 13.978v.514a2.06 2.06 0 0 1-2.066 2.066h-3.1a2.06 2.06 0 0 1-2.067-2.066v-3.1c0-1.145.922-2.066 2.067-2.066h1.827");
}

.kq4yk7byt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.203 5.5h4.345c1.145 0 2.067.922 2.067 2.066v4.346a2.06 2.06 0 0 1-2.067 2.066h-4.345a2.06 2.06 0 0 1-2.067-2.066V7.566c0-1.144.922-2.066 2.067-2.066M24.481 19.939v-.281c0-1.145.922-2.067 2.067-2.067h3.1c1.144 0 2.066.922 2.066 2.067v3.1a2.06 2.06 0 0 1-2.066 2.066h-.7");
}

.rqjs0ub5j {
  width: 22.563px;
  height: 22.561px;
  x: 6.385px;
  y: 19.939px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
