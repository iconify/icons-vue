<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4c0yd0ae"/><circle class="ynmar58zv"/><circle class="tad726sor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-time-to-leave" /></template>
<style>
.p4c0yd0ae {
  fill: currentColor;
  d: path("M18.92 5.01C18.72 4.42 18.16 4 17.5 4h-11c-.66 0-1.21.42-1.42 1.01L3 11v8c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h12v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-8zM6.85 6h10.29l1.04 3H5.81zM19 16H5v-4.66l.12-.34h13.77l.11.34z");
}

.tad726sor {
  cx: 16.5px;
  cy: 13.5px;
  r: 1.5px;
  fill: currentColor;
}

.ynmar58zv {
  cx: 7.5px;
  cy: 13.5px;
  r: 1.5px;
  fill: currentColor;
}

</style>
