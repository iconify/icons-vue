<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s3e43eb-h"/><path class="hto_2cc9h"/><path class="h1a-_zb3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tablet-x-two-tone" /></template>
<style>
.h1a-_zb3n {
  fill: currentColor;
  d: path("M13.5 8.5C13.5 9.3284 12.8284 10 12 10C11.1716 10 10.5 9.3284 10.5 8.5C10.5 7.6716 11.1716 7 12 7C12.8284 7 13.5 7.6716 13.5 8.5Z");
  stroke: none;
}

.hto_2cc9h {
  d: path("M22 10V7C22 5.34315 20.6569 4 19 4H5C3.34315 4 2 5.34315 2 7V17C2 18.6569 3.34315 20 5 20H12M22 14L16 20M16 14L22 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s3e43eb-h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 3C21.2091 3 23 4.79086 23 7V10C23 10.5523 22.5523 11 22 11H16C14.3431 11 13 12.3431 13 14V20C13 20.5523 12.5523 21 12 21H5C2.79086 21 1 19.2091 1 17V7C1 4.79086 2.79086 3 5 3H19Z");
  stroke: none;
}

</style>
