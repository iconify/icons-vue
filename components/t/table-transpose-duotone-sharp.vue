<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="afkqz-l1p"/><path class="rz1w-eb1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-transpose-duotone-sharp" /></template>
<style>
.afkqz-l1p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 2a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H11a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1ZM7 10a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V11a1 1 0 0 1 1-1Z");
}

.ft5dv1b6b {
  fill: none;
}

.rz1w-eb1w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 3h10v4H11Zm-8 8h4v10H3Zm15 8h-4v-4m0 4l6-6");
}

</style>
