<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lh8bb6b_h"/><path class="m8-upz77v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signpost-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lh8bb6b_h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 6h7l3 3l-3 3H4V6Z");
}

.m8-upz77v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 6h7l3 3l-3 3H4V6zm2-3v3m0 6v9");
}

</style>
