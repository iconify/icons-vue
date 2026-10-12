<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nhlux6b4j"/><path class="h8wp_s9rl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:onion" /></template>
<style>
.h8wp_s9rl {
  d: path("M10 9c-2 1.4-2.75 2.75-2.75 4.25c0 1 .35 1.9 1 2.6M14 9c2 1.4 2.75 2.75 2.75 4.25c0 1-.35 1.9-1 2.6M12 18.75v2.5M9.25 18.5l-1 2.25m6.5-2.25l1 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nhlux6b4j {
  d: path("M12 2.75c.5 1.75 1.25 2.75 2.75 3.5c3.25 1.5 5 4 5 7c0 3.5-3.5 5.5-7.75 5.5s-7.75-2-7.75-5.5c0-3 1.75-5.5 5-7c1.5-.75 2.25-1.75 2.75-3.5");
}

</style>
