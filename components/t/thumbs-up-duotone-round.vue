<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q79a1h-gd"/><path class="bvh2kac6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-up-duotone-round" /></template>
<style>
.bvh2kac6x {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 10a4 4 0 0 0 4-4V5a2 2 0 1 1 4 0v3a2 2 0 0 0 2 2h1a3 3 0 0 1 3 3v1l-1 5c-.233 1.163-1.488 2-3 2H9a2 2 0 0 1-2-2m0-9H5a2 2 0 0 0-2 2v7a2 2 0 1 0 4 0z");
}

.ft5dv1b6b {
  fill: none;
}

.q79a1h-gd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 6V5a3 3 0 1 1 6 0v3a.997.997 0 0 0 1 1h1a4 4 0 0 1 4 4v1q0 .1-.019.196l-1 5c-.087.43-.265.836-.523 1.191C19.675 21.475 18.309 22 17 22H9c-.74 0-1.45-.27-2-.764a3 3 0 0 1-3.225.502A3 3 0 0 1 2 19v-7a3 3 0 0 1 3-3h2a3 3 0 0 0 3-3");
}

</style>
