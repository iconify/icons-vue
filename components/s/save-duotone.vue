<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bqge3mbnq"/><path class="qc4hjmn4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:save-duotone" /></template>
<style>
.bqge3mbnq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 22a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h11c1.039 0 1.992.578 2.707 1.293l2 2C21.422 6.008 22 6.961 22 8v11a3 3 0 0 1-3 3Z");
}

.ft5dv1b6b {
  fill: none;
}

.qc4hjmn4b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11c.64 0 1.36.36 2 1l2 2c.64.64 1 1.36 1 2v11a2 2 0 0 1-2 2zm-5 0v-5a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v5M9 7h6");
}

</style>
