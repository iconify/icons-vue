<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nbgq1cblj"/><path class="x-nx1xbcx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-off-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nbgq1cblj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m16.342 13.342l-6.026-6.026L13.75 3v7H19ZM10.25 21v-7H5l2.658-3.342l6.026 6.026Z");
}

.x-nx1xbcx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.342 13.342L19 10h-5.25V3l-3.434 4.316m-2.658 3.342L5 14h5.25v7l3.434-4.316M2 5l17 17");
}

</style>
