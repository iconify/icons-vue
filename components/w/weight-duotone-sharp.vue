<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cxsx0ib9v"/><path class="mxtaw3b7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:weight-duotone-sharp" /></template>
<style>
.cxsx0ib9v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 7a1 1 0 0 1 .97.757l3 12A.998.998 0 0 1 20 21H4a.998.998 0 0 1-.97-1.243l3-12A1 1 0 0 1 7 7Z");
}

.ft5dv1b6b {
  fill: none;
}

.mxtaw3b7w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 8h10l3 12H4zm5 0a2 2 0 1 1 0-4m0 0a2 2 0 1 1 0 4");
}

</style>
