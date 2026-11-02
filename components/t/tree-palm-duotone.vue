<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tprzx83wj"/><path class="xpasmtb2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tree-palm-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.tprzx83wj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 6.316a5.77 5.77 0 0 1 3.291-1.749c2.263-.372 4.586.571 5.88 2.478a6 6 0 0 1 .787 1.669a1 1 0 0 1-1.068 1.28l-3.215-.357a8.5 8.5 0 0 1 2.323 6.429a1.002 1.002 0 0 1-1.751.593L12 9.519l-6.247 7.14a1.002 1.002 0 0 1-1.751-.593a8.45 8.45 0 0 1 .449-3.352a8.6 8.6 0 0 1 1.874-3.077l-3.215.357a1 1 0 0 1-1.068-1.28a6 6 0 0 1 .787-1.669a5.7 5.7 0 0 1 1.18-1.273a6 6 0 0 1 4.7-1.205A5.77 5.77 0 0 1 12 6.316");
}

.xpasmtb2f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8C9.875 4.211 4.241 4.837 3 9Zm9 1c-1.241-4.163-6.875-4.789-9-1Zm-9-1a7.52 7.52 0 0 0-7 8Zm7 8a7.52 7.52 0 0 0-7-8Zm-7 5V8");
}

</style>
