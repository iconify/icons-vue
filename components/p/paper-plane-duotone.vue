<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ky2voirrh"/><path class="xo4m92bbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paper-plane-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ky2voirrh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 4a1.58 1.58 0 0 1 2 2l-4 12c-.369 1.107-1.631 1.738-2 1l-3-6l-6-3c-.738-.369-.107-1.631 1-2Z");
}

.xo4m92bbn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6L6 8c-1.107.369-1.738 1.631-1 2l6 3l3 6c.369.738 1.631.107 2-1l4-12c.412-1.236-.764-2.412-2-2zm-1 7l3-3");
}

</style>
