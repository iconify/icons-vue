<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x14kz3byh"/><path class="zrsrjmbut"/><circle class="c9gbovbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-adf-scanner" /></template>
<style>
.c9gbovbnk {
  cx: 18px;
  cy: 16px;
  r: 1px;
  fill: currentColor;
}

.x14kz3byh {
  fill: currentColor;
  d: path("M8 6h8v6H8zm11 8H5c-.55 0-1 .45-1 1v3h16v-3c0-.55-.45-1-1-1m-1 3c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zrsrjmbut {
  fill: currentColor;
  d: path("M19 12h-1V4H6v8H5c-1.66 0-3 1.34-3 3v5h20v-5c0-1.66-1.34-3-3-3M8 6h8v6H8zm12 12H4v-3c0-.55.45-1 1-1h14c.55 0 1 .45 1 1z");
}

</style>
