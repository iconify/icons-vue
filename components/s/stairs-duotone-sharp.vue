<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bmcmh2min"/><path class="ages_qoas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stairs-duotone-sharp" /></template>
<style>
.ages_qoas {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21v-4h4v-4h4V9h4V5h6v16z");
}

.bmcmh2min {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 21v-4h4v-4h4V9h4V5h6v16Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
