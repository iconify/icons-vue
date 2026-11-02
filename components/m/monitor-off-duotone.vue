<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jf6d-rb8n"/><path class="sc11s0b_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-off-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jf6d-rb8n {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 3h12a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3");
}

.sc11s0b_p {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 17H6a2 2 0 0 1-2-2V6c0-.811.306-1.686 1-2m6 0h7a2 2 0 0 1 2 2v7M9 20h6M3 2l19 19");
}

</style>
