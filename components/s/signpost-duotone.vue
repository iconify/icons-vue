<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e5ts-tehe"/><path class="zhahw-bpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signpost-duotone" /></template>
<style>
.e5ts-tehe {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 6c.763 0 1.479.48 2 1l1 1a1.415 1.415 0 0 1 0 2l-1 1c-.521.52-1.237 1-2 1H6a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2Z");
}

.ft5dv1b6b {
  fill: none;
}

.zhahw-bpj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 6h6c.64 0 1.36.36 2 1l1 1a1.414 1.414 0 0 1 0 2l-1 1c-.64.64-1.36 1-2 1H6a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2zm2-3v3m0 6v9");
}

</style>
