<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j9umplbbp"/><path class="pd3y9sq9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:picture-in-picture-two-tone" /></template>
<style>
.j9umplbbp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 11L20 11C21.65685 11 23 12.34315 23 14L23 18C23 19.65685 21.65685 21 20 21L14 21C12.34315 21 11 19.65685 11 18L11 14C11 12.34315 12.34315 11 14 11Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pd3y9sq9k {
  d: path("M22 8V7C22 5.34315 20.65685 4 19 4H5C3.34315 4 2 5.34315 2 7V17C2 18.65685 3.34315 20 5 20H8M14 12L20 12C21.10457 12 22 12.89543 22 14L22 18C22 19.10457 21.10457 20 20 20L14 20C12.89543 20 12 19.10457 12 18L12 14C12 12.89543 12.89543 12 14 12Z");
}

</style>
