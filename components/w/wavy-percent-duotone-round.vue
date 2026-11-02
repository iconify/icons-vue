<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yz8d3towl"/><path class="hucfetb_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-percent-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hucfetb_r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 9c2.667 1.111 2.667 4.889 0 6c1.219 2.552-1.448 5.219-4 4c-1.111 2.667-4.889 2.667-6 0c-2.552 1.219-5.219-1.448-4-4c-2.667-1.111-2.667-4.889 0-6c-1.219-2.552 1.448-5.219 4-4c1.111-2.667 4.889-2.667 6 0c2.552-1.219 5.219 1.448 4 4m-4 0l-6 6m0-6h.01M15 15h.01");
}

.yz8d3towl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 15a3 3 0 0 1-4 4a3.25 3.25 0 0 1-6 0a3 3 0 0 1-4-4a3.25 3.25 0 0 1 0-6a3 3 0 0 1 4-4a3.25 3.25 0 0 1 6 0a3 3 0 0 1 4 4a3.25 3.25 0 0 1 0 6");
}

</style>
