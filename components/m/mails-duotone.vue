<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yy4lznc9j"/><path class="p7dx51ieu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mails-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p7dx51ieu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 11a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm1-1l4 4c.64.64 1.36 1 2 1s1.36-.36 2-1l4-4M7 5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v10");
}

.yy4lznc9j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 8h10a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-8a3 3 0 0 1 3-3");
}

</style>
