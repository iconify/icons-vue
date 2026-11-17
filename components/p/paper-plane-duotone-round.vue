<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m2flc7kgm"/><path class="a2oa0jy6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paper-plane-duotone-round" /></template>
<style>
.a2oa0jy6d {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6L6 8c-1.107.369-.476 2.262 1 3l2 1a6.7 6.7 0 0 1 3 3l1 2c.738 1.476 2.631 2.107 3 1l4-12c.412-1.236-.764-2.412-2-2zm-1 7l3-3");
}

.ft5dv1b6b {
  fill: none;
}

.m2flc7kgm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 4a1.58 1.58 0 0 1 2 2l-4 12c-.369 1.107-2.262.476-3-1l-1-2a6.7 6.7 0 0 0-3-3l-2-1c-1.476-.738-2.107-2.631-1-3Z");
}

</style>
