<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="p4ivvfb3y"/><path class="dlw0c4b8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-box-off-sharp-fill" /></template>
<style>
.dlw0c4b8s {
  d: path("M3 9V3M21 21H15M9 21H3V15M15 3H21V9M7 9.424L12 12M8.633 8.633L7 9.424V14.576L12 17V12M12.375 7.182L17 9.424V12.343M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p4ivvfb3y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 17L7 14.576V9.424L12 12V17Z");
  stroke: none;
}

</style>
