<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ii8ld06oh"/><path class="j835zw5-z"/><path class="lgr612izs"/><path class="a8uaxqbgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:petri-dish-outline-thin" /></template>
<style>
.a8uaxqbgz {
  d: path("M13 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ii8ld06oh {
  d: path("M21 9A9 9 0 0 1 3 9");
}

.j835zw5-z {
  d: path("M3 9h18");
}

.lgr612izs {
  d: path("M8 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
