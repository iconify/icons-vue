<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="fsumcib-j"/><path class="c1flt-p8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:person-standing-sharp-fill" /></template>
<style>
.c1flt-p8u {
  d: path("M6 12L18 12M12 12L12 17M7.6998 22.3753L12 17L16.3002 22.3753");
}

.fsumcib-j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.8284 7.8284C14.1057 8.5512 13.1043 9 12 9C9.7908 9 8 7.2092 8 5C8 2.7908 9.7908 1 12 1C14.2092 1 16 2.7908 16 5C16 6.1043 15.5512 7.1057 14.8284 7.8284Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
