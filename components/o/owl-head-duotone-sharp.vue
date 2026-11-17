<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="guge-hb1y"/><path class="oolx8wghy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:owl-head-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.guge-hb1y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 3c2.393 1.914 4.904 2.999 8 3c3.096-.001 5.607-1.086 8-3c1 2.5 1 5 1 8c0 5.5-4 10-9 10s-9-4.5-9-10c0-3 0-5.5 1-8");
}

.oolx8wghy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3c2.5 2 5 3 8 3s5.5-1 8-3c1 2.5 1 5 1 8c0 5.5-4 10-9 10s-9-4.5-9-10c0-3 0-5.5 1-8m2 8a2 2 0 1 0 4 0m0 0a2 2 0 1 0-4 0m8 0a2 2 0 1 0 4 0m0 0a2 2 0 1 0-4 0m-3 4h2l-1 2Z");
}

</style>
