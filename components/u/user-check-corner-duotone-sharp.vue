<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hknyg3b8r"/><path class="j4exjebda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-check-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hknyg3b8r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 7a4 4 0 1 1 8 0a4 4 0 0 1-8 0M3 21a6 6 0 0 1 6-6v6Z");
}

.j4exjebda {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 7a4 4 0 1 0 8 0a4 4 0 0 0-8 0M3 21a6 6 0 0 1 6-6m4 2l3 3l5-6");
}

</style>
