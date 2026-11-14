<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zbhzdyb6r"/><path class="r52zmr33h"/><path class="mg_-kvv5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wheelchair-basketball" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mg_-kvv5e {
  d: path("M18.75 2.25q-2 3.25 0 6.5");
}

.r52zmr33h {
  d: path("M13.005 12.345a5.5 5.5 0 1 1-9.01 0M15.5 5.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m0 0H22");
}

.zbhzdyb6r {
  d: path("M6.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 3.5v4.5H14l2.5 7");
}

</style>
