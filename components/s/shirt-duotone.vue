<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nh-czy3rg"/><path class="ystchfbxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shirt-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nh-czy3rg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m15.371 3.072l5 2C21.177 5.394 22 6.056 22 7v3a2 2 0 0 1-2 2h-1v6a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3v-6H4a2 2 0 0 1-2-2V7c0-.944.823-1.606 1.629-1.928l5-2A.998.998 0 0 1 10 4a2 2 0 1 0 4 0a1 1 0 0 1 1.371-.928");
}

.ystchfbxz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 4L4 6c-.604.242-1 .638-1 1v3a1 1 0 0 0 1 1h1a1 1 0 0 1 1 1v6a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2v-6a1 1 0 0 1 1-1h1a1 1 0 0 0 1-1V7c0-.362-.396-.758-1-1l-5-2m0 0a3 3 0 0 1-6 0");
}

</style>
