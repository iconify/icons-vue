<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ibkrzui2a"/><path class="xvdz842va"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-search-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ibkrzui2a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.028 6.141a5.244 5.244 0 1 1 3.943 9.718A5.244 5.244 0 0 1 9.028 6.14");
}

.xvdz842va {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7V3h4m10 0h4v4m0 10v4h-4M7 21H3v-4m5-9a4.243 4.243 0 1 1 6 6a4.243 4.243 0 0 1-6-6m6 6l3 3");
}

</style>
