<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="lbh94bg9m"/><path class="i0l307_8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-arrow-in-up-right-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i0l307_8d {
  d: path("M19 13L19 2L5 2L5 22L10 22M12 16L19 16L19 23M13.7071 21.2929L18.8536 16.1464");
}

.lbh94bg9m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 3L5 21C5 21.5523 5.4477 22 6 22L10 22L10 13L19 13L19 3C19 2.4477 18.5523 2 18 2L6 2C5.4477 2 5 2.4477 5 3ZM14.5 7L9.5 7L9.5 5L14.5 5L14.5 7Z");
  stroke: none;
}

</style>
