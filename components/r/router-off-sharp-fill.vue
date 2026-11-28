<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="d8npnwbwu"/><path class="zs_vtz9nu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:router-off-sharp-fill" /></template>
<style>
.d8npnwbwu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 21L2 21C1.4477 21 1 20.5523 1 20L1 12C1 11.4477 1.4477 11 2 11L11 11ZM9 16C9 15.4477 8.5523 15 8 15C7.4477 15 7 15.4477 7 16C7 16.5523 7.4477 17 8 17C8.5523 17 9 16.5523 9 16ZM14.6569 11L22 11C22.5523 11 23 11.4477 23 12L23 19.3431Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zs_vtz9nu {
  d: path("M7 12L5.3333 5.3333M17 12L17.1314 11.4745L19.1894 3.2425M1.7071 1.7071L22.2929 22.2929");
}

</style>
