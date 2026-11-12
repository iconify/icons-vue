<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tf9z-0a2r"/><path class="n53h-tcju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-pin-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n53h-tcju {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 20H4V4h16v4m-5 5h4v3l2 2h-8l2-2zm-1 0h6m-3 5v3");
}

.tf9z-0a2r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 3h16a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m11 10h4v3l2 2h-8l2-2Z");
}

</style>
