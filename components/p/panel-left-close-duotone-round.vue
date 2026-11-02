<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t8xi8pkds"/><path class="e13czwlkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-left-close-duotone-round" /></template>
<style>
.e13czwlkv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 8a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v8a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm5-4v16m7-11l-3 3l3 3");
}

.ft5dv1b6b {
  fill: none;
}

.t8xi8pkds {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 20a1 1 0 0 1-1 1H8a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h1a1 1 0 0 1 1 1Z");
}

</style>
