<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="so5iv2z7w"/><path class="v7oszcbpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mails-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.so5iv2z7w {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 21V9a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1");
}

.v7oszcbpv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9h14v12H3Zm0 0l6 6h2l6-6M7 5V3h14v12");
}

</style>
