<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="cpa8pz1nt"/><circle class="g8ll7b7pf"/><circle class="n3_7dmu3k"/><path class="ksstkbc_n"/><circle class="yfz3w9lrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-stream" /></template>
<style>
.cpa8pz1nt {
  cx: 20px;
  cy: 12px;
  r: 2px;
  fill: currentColor;
}

.g8ll7b7pf {
  cx: 4px;
  cy: 12px;
  r: 2px;
  fill: currentColor;
}

.ksstkbc_n {
  fill: currentColor;
  d: path("m7.89 14.65l-2.94 2.93a.996.996 0 1 0 1.41 1.41l2.94-2.93a.996.996 0 1 0-1.41-1.41M6.41 4.94A.996.996 0 1 0 5 6.35l2.93 2.94c.39.39 1.02.39 1.42 0c.38-.39.38-1.02-.01-1.41zm9.71 9.71c-.39-.39-1.02-.39-1.42 0a.996.996 0 0 0 0 1.41L17.64 19a.996.996 0 1 0 1.41-1.41zm-.06-5.32l2.99-2.98c.39-.4.39-1.03 0-1.42a.996.996 0 0 0-1.41 0l-2.99 2.98c-.39.39-.39 1.02 0 1.42c.39.39 1.02.39 1.41 0");
}

.n3_7dmu3k {
  cx: 12px;
  cy: 20px;
  r: 2px;
  fill: currentColor;
}

.yfz3w9lrl {
  cx: 12px;
  cy: 4px;
  r: 2px;
  fill: currentColor;
}

</style>
