<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yb1rnbc9a"/><path class="l4jh-xgmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-off-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l4jh-xgmr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10H3V3m7 1h11v6h-5m4 10H3v-6h11m-7 3h.01M2 2l20 20");
}

.yb1rnbc9a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 10V4h1l6 6Zm13 0l-6-6h11v6ZM3 20v-6h11l6 6Zm18-5l-1-1h1Z");
}

</style>
