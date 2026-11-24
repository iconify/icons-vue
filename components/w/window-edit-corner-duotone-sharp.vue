<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r27jrp7xs"/><path class="ki0q97bqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-edit-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ki0q97bqo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8V4h18v4M8 20H3V8m0 0h18m-8 13v-3l5-5l3 3l-5 5Z");
}

.r27jrp7xs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 4v4H3V4Zm-8 17v-3l5-5l3 3l-5 5Z");
}

</style>
