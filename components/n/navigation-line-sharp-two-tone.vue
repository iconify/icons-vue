<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="eh4gocc9q"/><path class="oypx3x1iw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:navigation-line-sharp-two-tone" /></template>
<style>
.eh4gocc9q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.999 8.43C12.384 8.43 12.735 8.65 12.901 9L18.902 21.57C19.072 21.93 19.017 22.35 18.762 22.65C18.506 22.95 18.097 23.07 17.719 22.96L12 21.28L6.281 22.96C5.903 23.07 5.494 22.95 5.238 22.65C4.983 22.35 4.928 21.93 5.098 21.57L11.097 9C11.263 8.65 11.614 8.43 11.999 8.43ZM12.999 7H10.999V1H12.999V7Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oypx3x1iw {
  d: path("M11.999 7V1M6 22L11.999 9.43L18 22L12 20.24L6 22Z");
}

</style>
