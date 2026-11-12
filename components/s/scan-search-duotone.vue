<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ibkrzui2a"/><path class="ve10xmj2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-search-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ibkrzui2a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.028 6.141a5.244 5.244 0 1 1 3.943 9.718A5.244 5.244 0 0 1 9.028 6.14");
}

.ve10xmj2r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7V5a2 2 0 0 1 2-2h2m10 0h2a2 2 0 0 1 2 2v2m0 10v2a2 2 0 0 1-2 2h-2M7 21H5a2 2 0 0 1-2-2v-2m5-9a4.243 4.243 0 1 1 6 6a4.243 4.243 0 0 1-6-6m6 6l3 3");
}

</style>
