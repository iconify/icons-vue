<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="l0-9netlr"/><path class="g80fpmbyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:picture-in-picture-off-sharp-fill" /></template>
<style>
.g80fpmbyk {
  d: path("M22 9L22 4L9.6569 4L8.6569 4M4 4L2 4L2 20L9 20M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l0-9netlr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 21L12 21C11.4477 21 11 20.5523 11 20L11 12C11 11.7238 11.1119 11.4738 11.2929 11.2929ZM14.6569 11L22 11C22.5523 11 23 11.4477 23 12L23 19.3431Z");
  stroke: none;
}

</style>
