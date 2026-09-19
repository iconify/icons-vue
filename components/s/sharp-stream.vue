<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="cpa8pz1nt"/><circle class="g8ll7b7pf"/><circle class="n3_7dmu3k"/><path class="fdfpz4b3k"/><circle class="yfz3w9lrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-stream" /></template>
<style>
.cpa8pz1nt {
  cx: 20px;
  cy: 12px;
  r: 2px;
  fill: currentColor;
}

.fdfpz4b3k {
  fill: currentColor;
  d: path("m13.943 8.619l4.404-4.392l1.413 1.416l-4.405 4.392zM8.32 9.68l.31.32l1.42-1.41l-4.02-4.04h-.01l-.31-.32l-1.42 1.41l4.02 4.05zm7.09 4.26L14 15.35l3.99 4.01l.35.35l1.42-1.41l-3.99-4.01zm-6.82.01l-4.03 4.01l-.32.33l1.41 1.41l4.03-4.02l.33-.32z");
}

.g8ll7b7pf {
  cx: 4px;
  cy: 12px;
  r: 2px;
  fill: currentColor;
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
