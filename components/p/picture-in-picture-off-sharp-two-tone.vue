<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uaq5esb7m"/><path class="wd6wyu5ry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:picture-in-picture-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uaq5esb7m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 21H12C11.448 21 11 20.552 11 20V12C11 11.724 11.112 11.474 11.293 11.293L21 21ZM14.657 11H22C22.552 11 23 11.448 23 12V19.343L14.657 11ZM21 9V5H9.657H8.657V3H9.657H22C22.552 3 23 3.448 23 4V9H21Z");
  stroke: none;
}

.wd6wyu5ry {
  d: path("M4 4H2V20H9M20 20H12V12M1.707 1.707L22.293 22.293");
}

</style>
