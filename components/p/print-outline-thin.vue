<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="msroekedq"/><path class="vgyler10s"/><path class="c7z9o8buo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:print-outline-thin" /></template>
<style>
.c7z9o8buo {
  d: path("M7 15h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.msroekedq {
  d: path("M6 5a3 3 0 0 1 3 -3h6a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H9a3 3 0 0 1 -3 -3");
}

.vgyler10s {
  d: path("M2 13a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
