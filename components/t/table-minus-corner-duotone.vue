<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iedi74b1o"/><path class="ow3qx6b0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-minus-corner-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iedi74b1o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 9H10v11a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3Z");
}

.ow3qx6b0p {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4h6a2 2 0 0 1 2 2v3M9 20H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h6M4 9h16M4 15h5m3-11v5m1 7h8");
}

</style>
