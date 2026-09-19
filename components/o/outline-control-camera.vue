<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkx9ztb_j"/><circle class="v4i2ew1ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-control-camera" /></template>
<style>
.lkx9ztb_j {
  fill: currentColor;
  d: path("M5.54 8.46L2 12l3.54 3.54l1.76-1.77L5.54 12l1.76-1.77zm6.46 10l-1.77-1.76l-1.77 1.76L12 22l3.54-3.54l-1.77-1.76zm6.46-10l-1.76 1.77L18.46 12l-1.76 1.77l1.76 1.77L22 12zm-10-2.92l1.77 1.76L12 5.54l1.77 1.76l1.77-1.76L12 2z");
}

.v4i2ew1ke {
  cx: 12px;
  cy: 12px;
  r: 3px;
  fill: currentColor;
}

</style>
