<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f2ruxmr6b"/><path class="n2o4ijxdo"/><path class="py17y4bbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-moon-two-tone" /></template>
<style>
.f2ruxmr6b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6C2 3.7909 3.7909 2 6 2H18C20.2091 2 22 3.7909 22 6V18C22 20.2091 20.2091 22 18 22H6C3.7909 22 2 20.2091 2 18V6Z");
  stroke: none;
}

.n2o4ijxdo {
  d: path("M6 3H18C19.6569 3 21 4.3431 21 6V18C21 19.6569 19.6569 21 18 21H6C4.3432 21 3 19.6569 3 18V6C3 4.3431 4.3432 3 6 3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.py17y4bbp {
  d: path("M17 12C17 14.7614 14.7614 17 12 17C9.2386 17 7 14.7614 7 12C7 9.2386 9.2386 7 12 7C10.8677 8.4154 10.9807 10.4559 12.2624 11.7376C13.5441 13.0193 15.5846 13.1323 17 12Z");
}

</style>
