<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="oclompb7u"/><circle class="qa-1pv6bo"/><circle class="on4fre1ek"/><path class="ah3klqb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-av-timer" /></template>
<style>
.ah3klqb7l {
  fill: currentColor;
  d: path("M12 3c-.55 0-1 .45-1 1v2c0 .55.45 1 1 1s1-.45 1-1v-.92c3.31.48 5.87 3.25 6 6.66c.14 3.85-3.03 7.2-6.88 7.26A6.996 6.996 0 0 1 5 12c0-1.68.59-3.22 1.58-4.42l4.71 4.72a.996.996 0 1 0 1.41-1.41L7.26 5.46c-.38-.38-1-.39-1.4-.02A8.9 8.9 0 0 0 3 12c0 5.04 4.14 9.12 9.21 9c4.7-.11 8.63-4.01 8.78-8.71C21.16 7.19 17.07 3 12 3");
}

.oclompb7u {
  cx: 12px;
  cy: 17px;
  r: 1px;
  fill: currentColor;
}

.on4fre1ek {
  cx: 17px;
  cy: 12px;
  r: 1px;
  fill: currentColor;
}

.qa-1pv6bo {
  cx: 7px;
  cy: 12px;
  r: 1px;
  fill: currentColor;
}

</style>
