<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="f_xf7xbbf"/><path class="z8dkv3pos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-off-sharp-two-tone" /></template>
<style>
.f_xf7xbbf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.2929 2.2929C2.1054 2.4804 2 2.7348 2 3L2 21C2 21.5523 2.4477 22 3 22L22 22ZM5.6569 2L21 2C21.5523 2 22 2.4477 22 3L22 18.3431Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z8dkv3pos {
  d: path("M21 21L3 21L3 3M3 9L9 9M3 15L15 15M12 12L12 21M1.7071 1.7071L22.2929 22.2929");
}

</style>
