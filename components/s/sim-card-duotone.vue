<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="euz-xzbmq"/><path class="bkz0g3b1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sim-card-duotone" /></template>
<style>
.bkz0g3b1y {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 12V5a2 2 0 0 1 2-2h7c.64 0 1.36.36 2 1l2 2c.64.64 1 1.36 1 2v11a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2zm4-2a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1Zm0 3h6");
}

.euz-xzbmq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 5a3 3 0 0 1 3-3h7c1.039 0 1.992.578 2.707 1.293l2 2C19.422 6.008 20 6.961 20 8v11a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
