<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b46nnkfrk"/><circle class="ovf7eoehk"/><circle class="enfz85iyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-face-2" /></template>
<style>
.b46nnkfrk {
  fill: currentColor;
  d: path("M21.97 13.52v-.04C23.21 12.38 24 10.78 24 9c0-3.31-2.69-6-6-6q-.39 0-.78.06a5.98 5.98 0 0 0-10.44 0Q6.39 3 6 3C2.69 3 0 5.69 0 9c0 1.78.79 3.38 2.02 4.48v.04A6 6 0 0 0 0 18c0 3.31 2.69 6 6 6c1.39 0 2.67-.48 3.69-1.28c.74.18 1.51.28 2.31.28s1.57-.1 2.31-.28c1.02.8 2.3 1.28 3.69 1.28c3.31 0 6-2.69 6-6c0-1.78-.79-3.38-2.03-4.48M12 21c-4.41 0-8-3.59-8-8c0-3.72 2.56-6.85 6-7.74v.05c0 3.34 2.72 6.06 6.06 6.06c1.26 0 2.45-.39 3.45-1.09c.31.86.49 1.77.49 2.72c0 4.41-3.59 8-8 8");
}

.enfz85iyf {
  cx: 15px;
  cy: 14px;
  r: 1.25px;
  fill: currentColor;
}

.ovf7eoehk {
  cx: 9px;
  cy: 14px;
  r: 1.25px;
  fill: currentColor;
}

</style>
