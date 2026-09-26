<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mpr28qpqr"/><path class="ywvyr1bfz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mic-two-tone" /></template>
<style>
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

.ywvyr1bfz {
  d: path("M9 5C9 3.343146 10.343146 2 12 2L12 2C13.656854 2 15 3.343146 15 5L15 11C15 12.656854 13.656854 14 12 14L12 14C10.343146 14 9 12.656854 9 11ZM19 11C19 14.865993 15.865993 18 12 18C8.134007 18 5 14.865993 5 11M12 18V22M8 22H16");
}

</style>
