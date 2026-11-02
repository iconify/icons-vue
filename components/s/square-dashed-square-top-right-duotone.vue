<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ltpa0-bib"/><path class="dgznfccyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-right-duotone" /></template>
<style>
.dgznfccyn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6V5a2 2 0 0 1 2-2h1m15 15v1a2 2 0 0 1-2 2h-1M6 21H5a2 2 0 0 1-2-2v-1m11 3h-4m-7-7v-4m7-5a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-7a2 2 0 0 1-2-2Z");
}

.ft5dv1b6b {
  fill: none;
}

.ltpa0-bib {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 2h7a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3h-7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3");
}

</style>
