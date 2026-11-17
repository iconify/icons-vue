<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sjdmwv_4k"/><path class="x92kl7tcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:security-camera-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.sjdmwv_4k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3.755 9.139a2.003 2.003 0 0 1 1.414-2.45L16.76 3.583a2 2 0 0 1 2.45 1.415l1.035 3.863a2.003 2.003 0 0 1-1.414 2.45L7.24 14.417a2 2 0 0 1-2.45-1.415Z");
}

.x92kl7tcp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.755 9.139a2 2 0 0 1 1.414-2.45L16.76 3.583a2 2 0 0 1 2.45 1.415l1.035 3.863a2 2 0 0 1-1.414 2.45L7.24 14.417a2 2 0 0 1-2.45-1.415ZM12 13.14V17h7m0-1v5M15.605 6.999l.518 1.932");
}

</style>
