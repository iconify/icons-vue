<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjm5ptp4h"/><circle class="yfz3w9lrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-man" /></template>
<style>
.yfz3w9lrl {
  cx: 12px;
  cy: 4px;
  r: 2px;
  fill: currentColor;
}

.zjm5ptp4h {
  fill: currentColor;
  d: path("M14 7h-4c-1.1 0-2 .9-2 2v5c0 .55.45 1 1 1h1v6c0 .55.45 1 1 1h2c.55 0 1-.45 1-1v-6h1c.55 0 1-.45 1-1V9c0-1.1-.9-2-2-2");
}

</style>
