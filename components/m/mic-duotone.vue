<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mpr28qpqr"/><path class="hrmastb5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mic-duotone" /></template>
<style>
.hrmastb5j {
  d: path("M19 11C19 14.866 15.866 18 12 18C8.134 18 5 14.866 5 11M12 18L12 22M8 22L16 22");
}

.mpr28qpqr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 5C8 2.790861 9.790861 1 12 1L12 1C14.209139 1 16 2.790861 16 5L16 11C16 13.209139 14.209139 15 12 15L12 15C9.790861 15 8 13.209139 8 11Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
