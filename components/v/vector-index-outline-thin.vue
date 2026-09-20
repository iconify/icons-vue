<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g4lz7ob4p"/><path class="knb00ei4h"/><path class="oq9ztqbxu"/><path class="korq7_l8k"/><path class="u84sg0ngq"/><path class="dy-bj6bwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vector-index-outline-thin" /></template>
<style>
.dy-bj6bwq {
  d: path("M14 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.g4lz7ob4p {
  d: path("M2 16a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.knb00ei4h {
  d: path("M5 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.korq7_l8k {
  d: path("M17 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.oq9ztqbxu {
  d: path("M11 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.u84sg0ngq {
  d: path("M8 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
