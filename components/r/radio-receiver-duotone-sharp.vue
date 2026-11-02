<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e94t96bfi"/><path class="olynd7bnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radio-receiver-duotone-sharp" /></template>
<style>
.e94t96bfi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 9v12H3V9ZM9 17a2 2 0 1 0 .001-3.999A2 2 0 0 0 9 17");
}

.ft5dv1b6b {
  fill: none;
}

.olynd7bnq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9h18v12H3Zm4 0l10-6M7 15a2 2 0 1 0 4 0a2 2 0 0 0-4 0m8-2h2m-2 4h2");
}

</style>
