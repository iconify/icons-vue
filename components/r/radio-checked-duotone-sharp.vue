<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mjo5zwbap"/><path class="bddvczbll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radio-checked-duotone-sharp" /></template>
<style>
.bddvczbll {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 12a8 8 0 1 0 16 0a8 8 0 0 0-16 0m5 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

.ft5dv1b6b {
  fill: none;
}

.mjo5zwbap {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 20a8 8 0 1 1 0-16a8 8 0 0 1 0 16");
}

</style>
