<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="x6pxic_zl"/><path class="aihg93b8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:voicemail-sharp-two-tone" /></template>
<style>
.aihg93b8y {
  d: path("M10 12C10 14.2091 8.2091 16 6 16C3.7909 16 2 14.2091 2 12C2 9.7909 3.7909 8 6 8C8.2091 8 10 9.7909 10 12ZM22 12C22 14.2091 20.2091 16 18 16C15.7909 16 14 14.2091 14 12C14 9.7909 15.7909 8 18 8C20.2091 8 22 9.7909 22 12ZM6 16L18 16");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x6pxic_zl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M11 12C11 14.7614 8.7614 17 6 17C3.2386 17 1 14.7614 1 12C1 9.2386 3.2386 7 6 7C8.7614 7 11 9.2386 11 12ZM23 12C23 14.7614 20.7614 17 18 17C15.2386 17 13 14.7614 13 12C13 9.2386 15.2386 7 18 7C20.7614 7 23 9.2386 23 12Z");
  stroke: none;
}

</style>
