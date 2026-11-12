<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ao1g_qbtk"/><path class="utmo7z3go"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-pin-corner-duotone-round" /></template>
<style>
.ao1g_qbtk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 7a5 5 0 1 1 10.001.001A5 5 0 0 1 4 7m11 6h4v3l1 1c.369.369-.262 1-1 1h-4c-.738 0-1.369-.631-1-1l1-1Zm-5 2v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1c0-1.862.731-3.636 2.05-4.95a6.9 6.9 0 0 1 2.225-1.499A6.9 6.9 0 0 1 9 14a1 1 0 0 1 1 1");
}

.ft5dv1b6b {
  fill: none;
}

.utmo7z3go {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 7a4 4 0 1 0 8 0a4 4 0 0 0-8 0M3 21a6 6 0 0 1 6-6m6-2h4v3l1 1c.369.369-.262 1-1 1h-4c-.738 0-1.369-.631-1-1l1-1zm-1 0h6m-3 5v3");
}

</style>
