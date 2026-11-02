<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g7jj86bvz"/><path class="qc-zzbbdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ruler-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g7jj86bvz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12.293 4.293a3.83 3.83 0 0 1 5.414 0l2 2a3.83 3.83 0 0 1 0 5.414l-8 8a3.83 3.83 0 0 1-5.414 0l-2-2a3.83 3.83 0 0 1 0-5.414Z");
}

.qc-zzbbdr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 9l4-4a2.83 2.83 0 0 1 4 0l2 2a2.83 2.83 0 0 1 0 4l-8 8a2.83 2.83 0 0 1-4 0l-2-2a2.83 2.83 0 0 1 0-4zm-4 4l2 2m2-6l2 2m2-6l2 2");
}

</style>
