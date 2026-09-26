<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gi_rbab8v"/><path class="owciiebyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:repeat-1-duotone" /></template>
<style>
.gi_rbab8v {
  stroke-opacity: 0.4;
  d: path("M3 18L17 18C19.2091 18 21 16.2091 21 14L21 9C21 6.7909 19.2091 5 17 5L16.5 5M6 15L3 18L6 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.owciiebyc {
  d: path("M11 4L12.5 3L12.5 9M3 11L3 9C3 6.7909 4.7909 5 7 5");
}

</style>
