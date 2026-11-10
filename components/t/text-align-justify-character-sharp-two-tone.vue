<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="klbet8b7x"/><path class="va8_1hbyr"/><path class="yuaegebky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-align-justify-character-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.klbet8b7x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 22H2V20H22V22ZM22 16H2V14H22V16ZM6.989 2C7.322 2 7.633 2.16 7.821 2.43C7.837 2.46 7.854 2.48 7.868 2.5L11.896 9.56L11.985 9.74L10.262 10.73L10.12 10.48L8.926 8H5.294L3.736 10.72L2.002 9.73L6.168 2.44C6.34 2.22 6.637 2.03 6.923 2C6.945 2 6.967 2 6.989 2Z");
  stroke: none;
}

.va8_1hbyr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 10H14V8H22V10ZM22 4H14V2H22V4Z");
  stroke: none;
}

.yuaegebky {
  d: path("M2.87 10.23L7 3L11.13 10.23M9.285 7H4.715M14 3H22M14 9H22M2 15H22M2 21H22");
}

</style>
