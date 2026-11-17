<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hrb3sl1bt"/><path class="rgn-eqb0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hrb3sl1bt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 3v15l-4 2c-.919.459-2-.081-2-1V7c.001-.85 1.349-1.674 2-2Zm6 3l4-2c.919-.459 2 .081 2 1v12c-.001.85-1.349 1.674-2 2l-4 2Z");
}

.rgn-eqb0a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 3l6 3l4-2c.919-.46 2 .081 2 1v12c0 .613-.774 1.387-2 2l-4 2l-6-3l-4 2c-.919.46-2-.081-2-1V7c0-.613.774-1.387 2-2zm0 0v15m6-12v15");
}

</style>
