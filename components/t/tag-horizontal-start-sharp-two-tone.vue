<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="alk7dvb9p"/><path class="gfnhmpggj"/><path class="mabku0myx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-horizontal-start-sharp-two-tone" /></template>
<style>
.alk7dvb9p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 3C22.5523 3 23 3.4477 23 4L23 20C23 20.5523 22.5523 21 22 21L9.1716 21C8.8874 21 8.6167 20.8791 8.427 20.6675L1.2554 12.6675C0.9149 12.2876 0.9149 11.7124 1.2554 11.3325L8.427 3.3325C8.6167 3.1209 8.8874 3 9.1716 3L22 3Z");
  stroke: none;
}

.gfnhmpggj {
  d: path("M22 4L9.1716 4L2 12L9.1716 20L22 20L22 4Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mabku0myx {
  fill: currentColor;
  d: path("M10.5 12C10.5 12.8284 9.8284 13.5 9 13.5C8.1716 13.5 7.5 12.8284 7.5 12C7.5 11.1716 8.1716 10.5 9 10.5C9.8284 10.5 10.5 11.1716 10.5 12Z");
  stroke: none;
}

</style>
