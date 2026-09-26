<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vqjnmwbwt"/><path class="upl6tcnav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-align-offset-top" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.upl6tcnav {
  d: path("M8 8H13M9 12H16M14 16H16");
}

.vqjnmwbwt {
  d: path("M21 6L21 18C21 19.6569 19.6569 21 18 21L6 21C4.34315 21 3 19.6569 3 18L3 6C3 4.34314 4.34315 3 6 3L18 3C19.6569 3 21 4.34315 21 6Z");
}

</style>
