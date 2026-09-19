<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqcv8_bld"/><path class="pbrnbxzcd"/><path class="i5d124wzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-sim-card-download" /></template>
<style>
.i5d124wzc {
  fill: currentColor;
  d: path("m12 17l4-4h-3V9l-2 .02V13H8z");
}

.pbrnbxzcd {
  fill: currentColor;
  d: path("M18 2h-8L4 8v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 18H6V8.83L10.83 4H18z");
}

.zqcv8_bld {
  fill: currentColor;
  d: path("M6 8.83V20h12V4h-7.17zm5 .19L13 9v4h3l-4 4l-4-4h3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
