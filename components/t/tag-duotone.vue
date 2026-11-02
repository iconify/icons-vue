<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="md74etlie"/><path class="p868c4orm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.md74etlie {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 4c.763 0 1.479.48 2 1l6 6a1.415 1.415 0 0 1 0 2l-6 6a1.415 1.415 0 0 1-2 0l-6-6c-.52-.521-1-1.237-1-2V6a2 2 0 0 1 2-2Zm-2 6a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.p868c4orm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 4h3c.64 0 1.36.36 2 1l6 6a1.414 1.414 0 0 1 0 2l-6 6a1.414 1.414 0 0 1-2 0l-6-6c-.64-.64-1-1.36-1-2V6a2 2 0 0 1 2-2zm0 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
