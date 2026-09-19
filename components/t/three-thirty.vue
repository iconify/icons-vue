<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="m0k3rdb8u"/><circle class="rt_37l3dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:three-thirty" /></template>
<style>
.m0k3rdb8u {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m16.973 36.5l-14.061-3.772a4 4 0 0 1-.912.718V58h-4V35.445a4 4 0 0 1-1.889-2.543L26 32.336l1.023-3.836l2.235.6c.224-.211.474-.389.741-.545V26h4v2.555a3.97 3.97 0 0 1 1.814 2.305L50 34.666z");
}

.rt_37l3dj {
  cx: 32px;
  cy: 32px;
  r: 3px;
  fill: currentColor;
}

</style>
