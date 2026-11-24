<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v_xeet77x"/><path class="u9i--ccxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-warning-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.u9i--ccxn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21c-3-2-7-6-7-11a7 7 0 0 1 14 0c0 5-4 9-7 11m0-14v3m0 3h.01");
}

.v_xeet77x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 21c-3-2-7-6-7-11a7 7 0 1 1 14 0c0 5-4 9-7 11");
}

</style>
