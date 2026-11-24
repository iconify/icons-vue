<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n57ml6boa"/><path class="nbyx_669o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:town-hall-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n57ml6boa {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 8a5 5 0 0 1 10 0v7h4v6H3v-6h4Z");
}

.nbyx_669o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 8v7h4v6H3v-6h4V8m3 13v-4h4v4M7 8a5 5 0 0 1 10 0m0 0A5 5 0 0 1 7 8m5-2v2h2");
}

</style>
