<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h51gqww2n"/><path class="bm68p9f0y"/><path class="nmiqo4b0f"/><path class="ec5tld62j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:revenue-goal-outline-thin" /></template>
<style>
.bm68p9f0y {
  d: path("M6.5 10.5v3");
}

.ec5tld62j {
  d: path("M17 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.h51gqww2n {
  d: path("M2 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nmiqo4b0f {
  d: path("M14 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
