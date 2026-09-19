<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hyb_4pkwa"/><circle class="vi_nxfq0r"/><path class="woyocpb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:toei-transportation" /></template>
<style>
.hyb_4pkwa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5C24 33.626 14.374 24 2.5 24C2.5 12.126 12.126 2.5 24 2.5S45.5 12.126 45.5 24C33.626 24 24 33.626 24 45.5");
}

.vi_nxfq0r {
  cx: 38.5px;
  cy: 38.5px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.woyocpb0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.85 34.5h5.3m-2.65 8v-8");
}

</style>
