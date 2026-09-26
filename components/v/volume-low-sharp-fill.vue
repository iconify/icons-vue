<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="guf8c5zsg"/><path class="vld2nvbwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:volume-low-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.guf8c5zsg {
  fill: currentColor;
  d: path("M2 8L5.5859 8L10.293 3.2947C10.923 2.6649 12 3.1111 12 4.0019L12 19.9981C12 20.8889 10.923 21.3351 10.293 20.7053L5.5859 16L2 16C1.4477 16 1 15.5523 1 15L1 9C1 8.4477 1.4477 8 2 8Z");
  stroke: none;
}

.vld2nvbwq {
  d: path("M15.0772 6.2227L15.8044 6.9091C17.2058 8.2316 18 10.0732 18 12C18 13.9268 17.2058 15.7684 15.8044 17.0909L15.0772 17.7773");
}

</style>
