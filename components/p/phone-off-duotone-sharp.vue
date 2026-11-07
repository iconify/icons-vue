<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zs9983bep"/><path class="gt5nqfb_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-off-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gt5nqfb_u {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.686 16.314A15.95 15.95 0 0 1 3 5V3h6l2 5l-3 3l2.5 2.5m6.214-.214L21 15v6h-2c-2.878 0-5.578-.76-7.91-2.09M2 22L22 2");
}

.zs9983bep {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m10.5 13.5l-2.814 2.814A15.95 15.95 0 0 1 3 5V3h6l2 5l-3 3Zm6.214-.214L21 15v6h-2a15.94 15.94 0 0 1-7.911-2.089Z");
}

</style>
