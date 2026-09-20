<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xfs8wlfhn"/><path class="ygr1bbcag"/><path class="htl7tccnk"/><path class="vqi6vft7m"/><path class="y0v87rbkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:secret-k8s-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.htl7tccnk {
  d: path("M8 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.vqi6vft7m {
  d: path("M11 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.xfs8wlfhn {
  d: path("M5 11.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.y0v87rbkg {
  d: path("M14 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ygr1bbcag {
  d: path("M8 9.5a4 4 0 0 1 8 0");
}

</style>
