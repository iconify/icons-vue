<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uwqrpj9qf"/><path class="j8pc8ekgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-info-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j8pc8ekgh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h2c1.28 0 2.36.36 3 1l3 3c.64.64 1 1.72 1 3v4c0 1.28-.36 2.36-1 3l-3 3c-.64.64-1.72 1-3 1h-4c-1.28 0-2.36-.36-3-1l-3-3c-.64-.64-1-1.72-1-3v-4c0-1.28.36-2.36 1-3l3-3c.64-.64 1.72-1 3-1zm0 5h.01M12 11v5");
}

.uwqrpj9qf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14 3c1.041 0 2.236.237 3 1l3 3c.763.764 1 1.959 1 3v4c0 1.041-.237 2.236-1 3l-3 3c-.764.763-1.959 1-3 1h-4c-1.041 0-2.236-.237-3-1l-3-3c-.763-.764-1-1.959-1-3v-4c0-1.041.237-2.236 1-3l3-3c.764-.763 1.959-1 3-1Z");
}

</style>
