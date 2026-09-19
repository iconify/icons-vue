<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="z59go1_xr"/><path class="h0bn7_biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-fiber-smart-record" /></template>
<style>
.h0bn7_biy {
  fill: currentColor;
  d: path("M17 4.26v2.09a5.99 5.99 0 0 1 0 11.3v2.09c3.45-.89 6-4.01 6-7.74s-2.55-6.85-6-7.74");
}

.z59go1_xr {
  cx: 9px;
  cy: 12px;
  r: 8px;
  fill: currentColor;
}

</style>
