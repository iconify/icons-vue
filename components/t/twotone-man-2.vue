<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w48vhzbzm"/><circle class="yfz3w9lrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-man-2" /></template>
<style>
.w48vhzbzm {
  fill: currentColor;
  d: path("M14 7h-4c-1.1 0-2 .9-2 2v6h2.5v7h3v-7H16V9c0-1.1-.9-2-2-2");
}

.yfz3w9lrl {
  cx: 12px;
  cy: 4px;
  r: 2px;
  fill: currentColor;
}

</style>
