<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d5hauobfu"/><path class="zao48575o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:video-off-duotone" /></template>
<style>
.d5hauobfu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 16a2.003 2.003 0 0 1-2 2H5a2.003 2.003 0 0 1-2-2V8a2.003 2.003 0 0 1 2-2Zm0-6l-4-4h2a2.003 2.003 0 0 1 2 2Zm0 0l4-2c.919-.459 2 .081 2 1v6c.001.268-.096.526-.274.726Z");
}

.ft5dv1b6b {
  fill: none;
}

.zao48575o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 16a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2m6 0h2a2 2 0 0 1 2 2v2m0 0l4-2c.919-.46 2 .081 2 1v6c0 .284-.104.533-.274.726M2 3l19 19");
}

</style>
