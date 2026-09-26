<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h2vfvv59n"/><path class="y0wdx0w6y"/><path class="vmayczbrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-left-close-dashed-two-tone" /></template>
<style>
.h2vfvv59n {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 2H18C20.20914 2 22 3.79086 22 6V18C22 20.20914 20.20914 22 18 22H6C3.79086 22 2 20.20914 2 18V6C2 3.79086 3.79086 2 6 2ZM6 3C4.34315 3 3 4.34315 3 6V18C3 19.65685 4.34315 21 6 21H9V3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vmayczbrg {
  d: path("M16 9L13 12L16 15");
}

.y0wdx0w6y {
  d: path("M9 3H6C4.34315 3 3 4.34315 3 6V18C3 19.6569 4.34315 21 6 21H9V3ZM18 3C19.6569 3 21 4.34315 21 6M21 18C21 19.6569 19.6569 21 18 21M13 3H14M13 21H14M21 10.5V13.5");
}

</style>
