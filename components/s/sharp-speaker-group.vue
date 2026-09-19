<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-mv0t39n"/><circle class="tbb72rihx"/><path class="r6fyrlbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-speaker-group" /></template>
<style>
.p-mv0t39n {
  fill: currentColor;
  d: path("M20 1H8v17.99h12zm-6 2c1.1 0 2 .89 2 2s-.9 2-2 2s-2-.89-2-2s.9-2 2-2m0 13.5c-2.21 0-4-1.79-4-4s1.79-4 4-4s4 1.79 4 4s-1.79 4-4 4");
}

.r6fyrlbnb {
  fill: currentColor;
  d: path("M6 5H4v18h12v-2H6z");
}

.tbb72rihx {
  cx: 14px;
  cy: 12.5px;
  r: 2.5px;
  fill: currentColor;
}

</style>
