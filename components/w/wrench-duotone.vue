<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dr_fskbcc"/><path class="d-cko6b3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wrench-duotone" /></template>
<style>
.d-cko6b3q {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12a5.385 5.385 0 0 1 7-7l-2 2l3 3l2-2a5.385 5.385 0 0 1-7 7m0 0l-5 5a2.121 2.121 0 1 1-3-3l5-5");
}

.dr_fskbcc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7.854 11.732a6.386 6.386 0 0 1 8.517-7.66a.998.998 0 0 1 .336 1.635L15.414 7L17 8.586l1.293-1.293a1 1 0 0 1 1.635.336c.304.753.459 1.559.457 2.371a6.386 6.386 0 0 1-8.117 6.146l-4.561 4.561a3.121 3.121 0 1 1-4.414-4.414Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
