<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lkjj9mb_g"/><path class="nf-yjwbzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pen-tool-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lkjj9mb_g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m4 4l10 3l3 6l-4 4l-6-3Z");
}

.nf-yjwbzq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 4l10 3l3 6l-4 4l-6-3Zm13 9l2 2a1.414 1.414 0 0 1 0 2l-2 2a1.414 1.414 0 0 1-2 0l-2-2M4 4l4 4m3 3h.01");
}

</style>
