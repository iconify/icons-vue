<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fiw1d34ee"/><path class="qne154bye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ship-duotone" /></template>
<style>
.fiw1d34ee {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 8a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v5a1.002 1.002 0 0 1-1.316.949L12 12.054l-5.684 1.895A1.002 1.002 0 0 1 5 13Z");
}

.ft5dv1b6b {
  fill: none;
}

.qne154bye {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 17l-1-3l9-3l9 3l-1 3M6 13V8a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v5M12 3v3m0 5v6M2 20c.5.5 1 1 2 1c2 0 2-2 4-2s2 2 4 2s2-2 4-2s2 2 4 2c1 0 1.5-.5 2-1");
}

</style>
