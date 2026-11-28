<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xxj8oxb4w"/><path clip-rule="evenodd" class="xcyd1c4eu"/><path class="igdm1gb8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vector-point-minus-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.igdm1gb8u {
  d: path("M15 19H23");
}

.xcyd1c4eu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 8H13C13.552 8 14 8.448 14 9V13C14 13.552 13.552 14 13 14H9C8.448 14 8 13.552 8 13V9C8 8.448 8.448 8 9 8H11Z");
  stroke: none;
}

.xxj8oxb4w {
  stroke-opacity: 0.4;
  d: path("M2 20V19C2 15 5 11 9 11M13 11C17 11 22 9 22 5V4");
}

</style>
