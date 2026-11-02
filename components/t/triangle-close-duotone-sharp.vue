<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ceot8m8vk"/><path class="vdj8zlbau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-close-duotone-sharp" /></template>
<style>
.ceot8m8vk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m12 2l10 18H2Z");
}

.ft5dv1b6b {
  fill: none;
}

.vdj8zlbau {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 2l10 18H2Zm-2 10l4 4m0-4l-4 4");
}

</style>
