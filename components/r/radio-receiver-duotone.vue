<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v8lgqhb2r"/><path class="p_w4ge05x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radio-receiver-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p_w4ge05x {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 11a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm4-2l10-6M7 15a2 2 0 1 0 4 0a2 2 0 0 0-4 0m8-2h2m-2 4h2");
}

.v8lgqhb2r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 9h14a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-8a2 2 0 0 1 2-2m4 8a2 2 0 1 0 .001-3.999A2 2 0 0 0 9 17");
}

</style>
