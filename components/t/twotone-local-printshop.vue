<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q60dec7pi"/><path class="qouoi6xyv"/><circle class="ts7gutx-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-local-printshop" /></template>
<style>
.q60dec7pi {
  fill: currentColor;
  d: path("M8 5h8v3H8zm11 5H5c-.55 0-1 .45-1 1v4h2v-2h12v2h2v-4c0-.55-.45-1-1-1m-1 2.5c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.qouoi6xyv {
  fill: currentColor;
  d: path("M19 8h-1V3H6v5H5c-1.66 0-3 1.34-3 3v6h4v4h12v-4h4v-6c0-1.66-1.34-3-3-3M8 5h8v3H8zm8 14H8v-4h8zm4-4h-2v-2H6v2H4v-4c0-.55.45-1 1-1h14c.55 0 1 .45 1 1z");
}

.ts7gutx-e {
  cx: 18px;
  cy: 11.5px;
  r: 1px;
  fill: currentColor;
}

</style>
