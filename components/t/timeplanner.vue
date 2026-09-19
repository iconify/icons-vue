<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ukozje5-j"/><rect class="f8n6_4bjx"/><rect class="pjo0-e6iz"/><path class="gh8amssbk"/><path class="px5dmgboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:timeplanner" /></template>
<style>
.f8n6_4bjx {
  width: 2.871px;
  height: 6.947px;
  x: 33.98px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.173px;
  ry: 1.173px;
}

.gh8amssbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.05 7.132h19.93m7.683 8.902v25.662c0 .444-.26.804-.581.804H6.917c-.32 0-.58-.36-.58-.804M11.33 7.132H6.918c-.32 0-.581.36-.581.805v33.736");
}

.pjo0-e6iz {
  width: 2.871px;
  height: 6.947px;
  x: 11.33px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.173px;
  ry: 1.173px;
}

.px5dmgboa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.85 7.132h4.253c.31 0 .56.36.56.805v33.736M6.337 16.034h35.326");
}

.ukozje5-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.718 29.587h6.816v6.982h-6.816z");
}

</style>
