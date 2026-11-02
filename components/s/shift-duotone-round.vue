<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="drnssgbkv"/><path class="pbl0l0b9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shift-duotone-round" /></template>
<style>
.drnssgbkv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 19a2 2 0 0 1-2-2v-2a2 2 0 0 0-2-2H6c-.738 0-1.369-.631-1-1l6-6a1.415 1.415 0 0 1 2 0l6 6c.369.369-.262 1-1 1h-1a2 2 0 0 0-2 2v2a2 2 0 0 1-2 2Z");
}

.ft5dv1b6b {
  fill: none;
}

.pbl0l0b9s {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19h-1a2 2 0 0 1-2-2v-2a2 2 0 0 0-2-2H6c-.738 0-1.369-.631-1-1l6-6a1.414 1.414 0 0 1 2 0l6 6c.369.369-.262 1-1 1h-1a2 2 0 0 0-2 2v2a2 2 0 0 1-2 2z");
}

</style>
