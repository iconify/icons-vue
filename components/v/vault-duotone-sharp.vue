<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="db99k3rxo"/><path class="nmxcg5c0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vault-duotone-sharp" /></template>
<style>
.db99k3rxo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 3h18v16H3Z");
}

.ft5dv1b6b {
  fill: none;
}

.nmxcg5c0u {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h18v16H3Zm4 16v2m10-2v2M8 11a4 4 0 1 1 8 0m0 0a4 4 0 1 1-8 0m4 0h.01");
}

</style>
