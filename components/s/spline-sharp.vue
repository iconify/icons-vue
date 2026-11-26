<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dz_9h9b6d"/><path clip-rule="evenodd" class="j339ybc_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:spline-sharp" /></template>
<style>
.dz_9h9b6d {
  d: path("M2 14L6 14L6 18L2 18ZM18 6L22 6L22 10L18 10ZM6 16C15 16 9 8 18 8");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j339ybc_n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 17C17.5 17.8285 16.8285 18.5 16 18.5C15.1715 18.5 14.5 17.8285 14.5 17C14.5 16.1715 15.1715 15.5 16 15.5C16.8285 15.5 17.5 16.1715 17.5 17ZM9.5 7C9.5 7.8285 8.8285 8.5 8 8.5C7.1715 8.5 6.5 7.8285 6.5 7C6.5 6.1715 7.1715 5.5 8 5.5C8.8285 5.5 9.5 6.1715 9.5 7Z");
  stroke: none;
}

</style>
