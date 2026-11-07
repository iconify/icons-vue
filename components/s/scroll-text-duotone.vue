<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rukx1o5oe"/><path class="kxgr870tv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scroll-text-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kxgr870tv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 17V5a2 2 0 0 0-2-2H5m2 2v14M7 5a2 2 0 1 0-4 0v2a1 1 0 0 0 1 1h3m0 11a2 2 0 1 0 4 0v-1a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v1a2 2 0 0 1-2 2H9m1-13h5m-5 4h5");
}

.rukx1o5oe {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 2a3 3 0 0 1 3 3v11h1a2 2 0 0 1 2 2v1a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3V9H4a2 2 0 0 1-2-2V5a3 3 0 0 1 3-3Z");
}

</style>
