<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a7juzblmp"/><path class="nwr6yccba"/><path class="xec9ltb1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wellbeing-goal-outline-thin" /></template>
<style>
.a7juzblmp {
  d: path("M5 12a3 3 0 0 1 6 0 3 3 0 0 1 6 0l-6 6Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nwr6yccba {
  d: path("M20 7v7");
}

.xec9ltb1w {
  d: path("m20 3 -4 4h4Z");
}

</style>
