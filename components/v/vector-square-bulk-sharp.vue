<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gwhycgb1s"/><path class="upuheg75n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vector-square-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gwhycgb1s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 5v2h2v10h-2v2H7v-2H5V7h2V5Z");
}

.upuheg75n {
  d: path("M7 2a1 1 0 0 1 1 1v1h8V3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-1v8h1a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-1H8v1a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h1V8H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm1 5a1 1 0 0 1-1 1H6v8h1a1 1 0 0 1 1 1v1h8v-1a1 1 0 0 1 1-1h1V8h-1a1 1 0 0 1-1-1V6H8Z");
}

</style>
