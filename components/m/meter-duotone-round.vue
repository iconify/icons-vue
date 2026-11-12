<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xz9_wf07k"/><path class="o56mawbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.o56mawbpt {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v9a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm5-5v1m8-1v1M6 8a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1Zm4-1v5m4-5v5m-6 5h8");
}

.xz9_wf07k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 3h10a5 5 0 0 1 5 5v9a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5");
}

</style>
