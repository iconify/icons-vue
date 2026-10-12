<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="dvna8tbyr"/><path class="ba-m2ubid"/><path class="q4vb7_buy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:octopus-marine" /></template>
<style>
.ba-m2ubid {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 9.5h.01m4.99 0h.01");
}

.dvna8tbyr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 12.5c-.5-4.5 2-8.75 6.75-8.75S19.25 8 18.75 12.5Z");
}

.q4vb7_buy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12.5c0 2.5-1.25 4.25-3.5 4.25m6.75-4.25V15c0 1.5-.75 2.5-2 3m5.5-5.5V15c0 1.5.75 2.5 2 3M17 12.5c0 2.5 1.25 4.25 3.5 4.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
