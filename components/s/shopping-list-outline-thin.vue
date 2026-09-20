<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="diipsobkl"/><path class="pvve3lboo"/><path class="c6uw-ccfl"/><path class="n8sqmebht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shopping-list-outline-thin" /></template>
<style>
.c6uw-ccfl {
  d: path("M7 14h10");
}

.diipsobkl {
  d: path("M5 3v18h14V3Z");
}

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

.pvve3lboo {
  d: path("m7 8 2 2 4 -4");
}

</style>
