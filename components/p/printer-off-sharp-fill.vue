<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="t1350f78f"/><path class="f_049ab8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:printer-off-sharp-fill" /></template>
<style>
.f_049ab8k {
  d: path("M6.6569 2L7.6569 2L14 2L18 6L18 10M18 18L18 22L6 22L6 15L15 15M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t1350f78f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.0001 9.0001L16 16L7 16L7 20L2 20C1.4477 20 1 19.5523 1 19L1 10C1 9.4517 1.4413 9.0065 1.988 9.0001ZM20 20L17 20L17 17ZM12.6569 9L22 9C22.5523 9 23 9.4477 23 10L23 19C23 19.1038 22.9842 19.2039 22.9549 19.298Z");
  stroke: none;
}

</style>
