<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zi6v5k-is"/><path class="caxzf3hfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tower-sharp-two-tone" /></template>
<style>
.caxzf3hfk {
  d: path("M18 22H23M18 22V8M18 22H14H10H6M18 8H6M18 8H20.972L12 2L3 8H6M6 22H1M6 22V8M10 18H14V14C14 12.9 13.105 12 12 12C10.895 12 10 12.9 10 14V18Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zi6v5k-is {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.506 1.13C11.819 0.98 12.262 0.97 12.556 1.17L21.528 7.17C21.894 7.41 22.057 7.87 21.929 8.29C21.801 8.71 21.413 9 20.973 9H19V21H23V23H1V21H5V9H3C2.559 9 2.171 8.71 2.043 8.29C1.915 7.87 2.079 7.41 2.445 7.17L11.506 1.13Z");
  stroke: none;
}

</style>
