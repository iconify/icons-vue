<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t46_l1b3y"/><path class="tz8sdybnu"/><path class="g-g6w6buq"/><path class="p8hpvcvzr"/><path class="n8sqmebht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stack-frame-outline-regular" /></template>
<style>
.g-g6w6buq {
  d: path("M7 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.n8sqmebht {
  d: path("M7 18h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p8hpvcvzr {
  d: path("M11.5 11h5");
}

.t46_l1b3y {
  d: path("M7 4h10");
}

.tz8sdybnu {
  d: path("M4 11a3 3 0 0 1 3 -3h10a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3");
}

</style>
