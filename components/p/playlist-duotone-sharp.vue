<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lccnmmbra"/><path class="b_uz_rghb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playlist-duotone-sharp" /></template>
<style>
.b_uz_rghb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6h18M3 12h8m-8 6h8m4-8v8l6-4z");
}

.ft5dv1b6b {
  fill: none;
}

.lccnmmbra {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m15 10l6 4l-6 4Z");
}

</style>
