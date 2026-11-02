<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wd93ipqqe"/><path class="us5vywibh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tags-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.us5vywibh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 6h2c.64 0 1.36.36 2 1l4 4a1.414 1.414 0 0 1 0 2l-4 4a1.414 1.414 0 0 1-2 0l-4-4c-.64-.64-1-1.36-1-2V8a2 2 0 0 1 2-2zm1 4h.01M15 6l5 5a1.414 1.414 0 0 1 0 2l-5 5");
}

.wd93ipqqe {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 5c1.039 0 1.992.578 2.707 1.293l4 4a2.414 2.414 0 0 1 0 3.414l-4 4a2.414 2.414 0 0 1-3.414 0l-4-4C2.578 12.992 2 12.039 2 11V8a3 3 0 0 1 3-3Z");
}

</style>
