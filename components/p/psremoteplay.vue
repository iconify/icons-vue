<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p71p8pkoh"/><circle class="yai5wgr3c"/><circle class="dfo5u451s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:psremoteplay" /></template>
<style>
.dfo5u451s {
  cx: 23.985px;
  cy: 8.379px;
  r: 0.75px;
  fill: currentColor;
}

.p71p8pkoh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.56 21.993a7.274 7.274 0 0 0-12.23-4.336H18.66a7.28 7.28 0 0 0-4.997-1.999h0a7.294 7.294 0 0 0-7.244 6.335h0L4.511 37.22c-.32 3.886 6.525 3.996 7.804 1.319l3.087-4.897a4.32 4.32 0 0 1 3.587-2.298h9.992a4.24 4.24 0 0 1 3.617 2.298l3.088 4.896c1.278 2.658 8.123 2.568 7.803-1.318Z");
}

.yai5wgr3c {
  cx: 23.985px;
  cy: 12.853px;
  r: 0.75px;
  fill: currentColor;
}

</style>
