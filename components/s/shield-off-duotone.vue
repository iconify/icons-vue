<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w3kb-jhyo"/><path class="cxrwhzbdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-off-duotone" /></template>
<style>
.cxrwhzbdh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 3h8a2 2 0 0 1 2 2v5c0 .958.2 1.16 0 2m-2 5c-1.441 1.847-3.721 2.987-6 4c-4.5-2-8-5.5-8-11V5c0-.552.638-.638 1-1M3 2l19 19");
}

.ft5dv1b6b {
  fill: none;
}

.w3kb-jhyo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 2a3 3 0 0 1 3 3v5c-.001 5.712-3.495 9.647-8.594 11.914a1 1 0 0 1-.812 0C6.495 19.647 3.001 15.712 3 10V5a3 3 0 0 1 3-3Z");
}

</style>
