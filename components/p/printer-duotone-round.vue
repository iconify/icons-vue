<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b940g53gt"/><path class="kib73vp7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:printer-duotone-round" /></template>
<style>
.b940g53gt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 6a5 5 0 0 1 5 5v3a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4v-3a5 5 0 0 1 5-5Zm-7 6h4a1 1 0 0 0 0-2h-4a1 1 0 0 0 0 2");
}

.ft5dv1b6b {
  fill: none;
}

.kib73vp7f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 17a3 3 0 0 1-3-3v-3a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v3a3 3 0 0 1-3 3M6 7a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4m-8 4h4m-8 7a3 3 0 0 1 3-3h6a3 3 0 0 1 0 6H9a3 3 0 0 1-3-3");
}

</style>
