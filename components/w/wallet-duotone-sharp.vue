<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="daa2uvb1b"/><path class="ei0a2abzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wallet-duotone-sharp" /></template>
<style>
.daa2uvb1b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 4h18v16H3Z");
}

.ei0a2abzb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4h18v16H3Zm18 5h-6v6h6m-3-3h.01");
}

.ft5dv1b6b {
  fill: none;
}

</style>
