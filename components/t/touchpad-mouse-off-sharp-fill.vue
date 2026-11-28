<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="xzqvu2ltx"/><path class="puocw8bfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:touchpad-mouse-off-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.puocw8bfr {
  d: path("M11 16H2V2.414M6.657 2H20V7M1.707 1.707L22.293 22.293");
}

.xzqvu2ltx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.535 21.535C20.632 22.439 19.38 23 18 23C15.239 23 13 20.761 13 18V14C13 13.687 13.029 13.381 13.084 13.084L21.535 21.535ZM14.297 10.64C15.212 9.633 16.532 9 18 9C20.761 9 23 11.239 23 14V18C23 18.413 22.95 18.814 22.855 19.198L14.297 10.64Z");
  stroke: none;
}

</style>
