<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zaavu1g8i"/><path class="jguyt6bee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:train-front-off-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jguyt6bee {
  fill: currentColor;
  d: path("M10 13.5C10 14.3284 9.3284 15 8.5 15C7.6716 15 7 14.3284 7 13.5C7 12.6716 7.6716 12 8.5 12C9.3284 12 10 12.6716 10 13.5Z");
  stroke: none;
}

.zaavu1g8i {
  d: path("M18 18L4 18L4 4M4 9L9 9M4 5L1 5M7 18L4.7236 22.5528M17 18L19.2764 22.5528M6.6569 2L20 2L20 15.3431M13.6569 9L20 9M20 5L23 5M1.7071 1.7071L22.2929 22.2929");
}

</style>
