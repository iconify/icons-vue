<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y5f6c-4ni"/><path class="s-6rb6b-a"/><path class="n8sqmebht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pet-bowl-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n8sqmebht {
  d: path("M7 18h10");
}

.s-6rb6b-a {
  d: path("M4 8h16c0 4 -3 7 -8 7s-8 -3 -8 -7");
}

.y5f6c-4ni {
  fill: currentColor;
  d: path("M4 8h16c0 4 -3 7 -8 7s-8 -3 -8 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
