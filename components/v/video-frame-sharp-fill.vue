<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="g3nd9eb8u"/><path clip-rule="evenodd" class="sryf-rxyv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:video-frame-sharp-fill" /></template>
<style>
.g3nd9eb8u {
  d: path("M3 9V3H9M15 3H21V9M9 21H3V15M18 14V21M21.293 17.707L18 21L14.707 17.707");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sryf-rxyv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.981 13.823L8.445 15.77C8.297 15.851 8.131 15.894 7.963 15.894C7.41 15.894 6.963 15.446 6.963 14.894V7.106C6.963 6.554 7.41 6.106 7.963 6.106C8.131 6.106 8.297 6.149 8.445 6.23L15.518 10.124C15.837 10.3 16.036 10.635 16.036 11C16.036 11.364 15.837 11.7 15.518 11.876L11.981 13.823Z");
  stroke: none;
}

</style>
