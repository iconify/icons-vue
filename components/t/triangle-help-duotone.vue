<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gg1kvqb1y"/><path class="p04j9-b_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-help-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gg1kvqb1y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m13.728 4.992l7 12A2.001 2.001 0 0 1 19 20H5a1.999 1.999 0 0 1-1.728-3.008l7-12a2.003 2.003 0 0 1 3.456 0");
}

.p04j9-b_i {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m13.728 4.992l7 12C21.505 18.326 20.544 20 19 20H5c-1.544 0-2.505-1.674-1.728-3.008l7-12c.772-1.323 2.684-1.323 3.456 0M10 12a2 2 0 1 1 2 2m0 3h.01");
}

</style>
