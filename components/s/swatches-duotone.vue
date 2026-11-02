<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h52q3wbup"/><path class="k-a_8ebhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:swatches-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h52q3wbup {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 5a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v12a5 5 0 0 1-10 0Z");
}

.k-a_8ebhq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 17V5a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v12a4 4 0 1 1-8 0m4 0h.01M11 9l3-3a1.414 1.414 0 0 1 2 0l3 3a1.414 1.414 0 0 1 0 2L9 21m7-7h3a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H7");
}

</style>
