<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dnce5r20g"/><path class="tfj6n3bij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:security-key-sharp-two-tone" /></template>
<style>
.dnce5r20g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 17L6 17C5.4477 17 5 16.5523 5 16L5 2C5 1.4477 5.4477 1 6 1L18 1C18.5523 1 19 1.4477 19 2L19 9L19 16C19 16.5523 18.5523 17 18 17L16 17L16 22C16 22.5523 15.5523 23 15 23L9 23C8.4477 23 8 22.5523 8 22Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tfj6n3bij {
  d: path("M6 2L18 2L18 16L6 16ZM9 16L9 22L15 22L15 16M14 9C14 10.1046 13.1046 11 12 11C10.8954 11 10 10.1046 10 9C10 7.8954 10.8954 7 12 7C13.1046 7 14 7.8954 14 9Z");
}

</style>
