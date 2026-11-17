<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vg1lh6vdz"/><path class="ey4y9ubwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sword-duotone" /></template>
<style>
.ey4y9ubwa {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14L17 4c.64-.64 1.36-1 2-1h2v2c0 .64-.36 1.36-1 2L10 17m-5-5l7 7m-4-3l-4 4m-1-1l2 2");
}

.ft5dv1b6b {
  fill: none;
}

.vg1lh6vdz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 14L17 4c.521-.52 1.237-1 2-1h2v2c0 .763-.48 1.479-1 2L10 17Z");
}

</style>
