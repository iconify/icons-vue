<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="daf2jp9-x"/><path class="epp4f_bbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:watch-duotone-sharp" /></template>
<style>
.daf2jp9-x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 12a5 5 0 1 1 10.001.001A5 5 0 0 1 7 12");
}

.epp4f_bbm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 0 0-10 0m2-4V3h6v5m-6 8v5h6v-5m-3-6v2h2");
}

.ft5dv1b6b {
  fill: none;
}

</style>
