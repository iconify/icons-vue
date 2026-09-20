<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sxa4vgbew"/><path class="epqlf4buo"/><path class="fe9c5cduf"/><path class="w8v40bcti"/><path class="yjqw0hqbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:weak-label-duotone-thin" /></template>
<style>
.epqlf4buo {
  fill: currentColor;
  d: path("M7.5 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fe9c5cduf {
  d: path("M3 7h13l5 5 -5 5H3Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sxa4vgbew {
  fill: currentColor;
  d: path("M3 7h13l5 5 -5 5H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.w8v40bcti {
  d: path("M6 10.5A2.5 2.5 0 1 1 8.5 13");
}

.yjqw0hqbw {
  d: path("M7.5 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
