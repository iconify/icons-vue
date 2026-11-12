<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cjfs5hb_d"/><path class="mql7lbbhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-plus-corner-duotone-round" /></template>
<style>
.cjfs5hb_d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 3h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8m3 18H6a4 4 0 0 1 0-8h3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1");
}

.ft5dv1b6b {
  fill: none;
}

.mql7lbbhi {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7a3 3 0 0 1 3-3h12a3 3 0 0 1 0 6H6a3 3 0 0 1-3-3m0 7h6m0 6H6a3 3 0 0 1-3-3v-3m4-7h.01M7 17h.01M13 17h8m-4-4v8");
}

</style>
