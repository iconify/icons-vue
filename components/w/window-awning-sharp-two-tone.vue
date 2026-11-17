<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s59f6acdq"/><path class="c92vcfb3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-awning-sharp-two-tone" /></template>
<style>
.c92vcfb3u {
  d: path("M4 21V3H20V21M1 21H23M4 9H20M12 9V21M4 15H20");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s59f6acdq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 2C20.552 2 21 2.448 21 3V20H23V22H1V20H3V3C3 2.448 3.448 2 4 2H20Z");
  stroke: none;
}

</style>
