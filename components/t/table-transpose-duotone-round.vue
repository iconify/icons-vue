<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xagdlp4_j"/><path class="euo_v4biu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-transpose-duotone-round" /></template>
<style>
.euo_v4biu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 5a2 2 0 0 1 2-2h6a2 2 0 1 1 0 4h-6a2 2 0 0 1-2-2m-8 8a2 2 0 1 1 4 0v6a2 2 0 1 1-4 0Zm15 6h-4v-4m0 4l6-6");
}

.ft5dv1b6b {
  fill: none;
}

.xagdlp4_j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 3h6a2 2 0 1 1 0 4h-6a2 2 0 1 1 0-4M3 13a2 2 0 1 1 4 0v6a2 2 0 1 1-4 0Z");
}

</style>
