<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i0g5c0bye"/><path class="flnsg9btl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:serial-port-off-sharp-two-tone" /></template>
<style>
.flnsg9btl {
  d: path("M18 18L4.159 18L2.0015 6L6 6M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i0g5c0bye {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 19L4.159 19C3.675 19 3.2604 18.6533 3.1748 18.177L1.0173 6.177C1.0068 6.1186 1.0015 6.0593 1.0015 6C1.0015 5.4477 1.4492 5 2.0015 5L5 5ZM8.7426 5L12 5L21.9985 5C22.5508 5 22.9985 5.4477 22.9985 6C22.9985 6.0593 22.9932 6.1186 22.9827 6.177L20.992 17.2494Z");
  stroke: none;
}

</style>
