<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="put6okbug"/><path class="py17y4bbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-moon" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.put6okbug {
  d: path("M6 3H18C19.6569 3 21 4.3431 21 6V18C21 19.6569 19.6569 21 18 21H6C4.3431 21 3 19.6569 3 18V6C3 4.3431 4.3431 3 6 3Z");
}

.py17y4bbp {
  d: path("M17 12C17 14.7614 14.7614 17 12 17C9.2386 17 7 14.7614 7 12C7 9.2386 9.2386 7 12 7C10.8677 8.4154 10.9807 10.4559 12.2624 11.7376C13.5441 13.0193 15.5846 13.1323 17 12Z");
}

</style>
