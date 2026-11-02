<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lla1cob_j"/><path class="utf47neop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:martini-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lla1cob_j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 5a1.002 1.002 0 0 1 .707 1.707l-5 5a1 1 0 0 1-1.414 0l-5-5A1 1 0 0 1 7 5Z");
}

.utf47neop {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3h16l-8 8zm8 8v10m-4 0h8M7 6h10");
}

</style>
