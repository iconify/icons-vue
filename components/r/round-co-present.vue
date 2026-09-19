<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic9rndbss"/><circle class="l31vcjxth"/><path class="gsi4w0b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-co-present" /></template>
<style>
.gsi4w0b8j {
  fill: currentColor;
  d: path("M15.39 16.56C13.71 15.7 11.53 15 9 15s-4.71.7-6.39 1.56A2.97 2.97 0 0 0 1 19.22V22h16v-2.78c0-1.12-.61-2.15-1.61-2.66");
}

.ic9rndbss {
  fill: currentColor;
  d: path("M21 3H3c-1.1 0-2 .9-2 2v8h2V5h18v16c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2");
}

.l31vcjxth {
  cx: 9px;
  cy: 10px;
  r: 4px;
  fill: currentColor;
}

</style>
