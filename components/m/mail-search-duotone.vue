<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="grsmu9bfc"/><path class="zg_1vbbfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-search-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.grsmu9bfc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M22 17a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h5a.998.998 0 0 1 .986 1.164a5 5 0 0 0 .174 2.387a5.08 5.08 0 0 0 6.194 3.348a1 1 0 0 1 .973.257l1.259 1.258A2 2 0 0 0 21 13a1 1 0 0 1 1 1Z");
}

.zg_1vbbfh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 14v3a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h5M4 6l4 4c.64.64 1.36 1 2 1h2m2-7a2.828 2.828 0 1 1 4 4a2.828 2.828 0 0 1-4-4m4 4l3 3");
}

</style>
