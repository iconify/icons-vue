<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b1z4meb2q"/><path class="upl6tcnav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-align-offset-top-duotone" /></template>
<style>
.b1z4meb2q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 2C20.2091 2 22 3.79086 22 6L22 18C22 20.2091 20.2091 22 18 22L6 22C3.79086 22 2 20.2091 2 18L2 6C2 3.79086 3.79086 2 6 2L18 2Z");
  stroke: none;
}

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

</style>
