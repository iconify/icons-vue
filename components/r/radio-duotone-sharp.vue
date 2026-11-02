<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m3qgi09hz"/><path class="vq9zm5b1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radio-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m3qgi09hz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 12a8 8 0 1 1 16 0a8 8 0 0 1-16 0");
}

.vq9zm5b1v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 12a8 8 0 1 0 16 0a8 8 0 0 0-16 0");
}

</style>
