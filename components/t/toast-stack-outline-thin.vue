<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c-bzonblr"/><path class="kqaa63eeo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:toast-stack-outline-thin" /></template>
<style>
.c-bzonblr {
  d: path("M2 14.5A2.5 2.5 0 0 1 4.5 12h11a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-11A2.5 2.5 0 0 1 2 14.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kqaa63eeo {
  d: path("M6 6.5A2.5 2.5 0 0 1 8.5 4h11A2.5 2.5 0 0 1 22 6.5 2.5 2.5 0 0 1 19.5 9h-11A2.5 2.5 0 0 1 6 6.5");
}

</style>
