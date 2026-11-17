<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ak7sw2brr"/><path class="ystchfbxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shirt-duotone" /></template>
<style>
.ak7sw2brr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 4a3 3 0 1 0 6 0l5 2c.384.154.999.52 1 1v3a1 1 0 0 1-1 1h-1a1 1 0 0 0-1 1v6a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-6a1 1 0 0 0-1-1H4a1 1 0 0 1-1-1V7c.001-.48.616-.846 1-1Z");
}

.ft5dv1b6b {
  fill: none;
}

.ystchfbxz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 4L4 6c-.604.242-1 .638-1 1v3a1 1 0 0 0 1 1h1a1 1 0 0 1 1 1v6a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2v-6a1 1 0 0 1 1-1h1a1 1 0 0 0 1-1V7c0-.362-.396-.758-1-1l-5-2m0 0a3 3 0 0 1-6 0");
}

</style>
