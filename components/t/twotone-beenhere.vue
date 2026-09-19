<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9p3kgbme"/><path class="fmoxa2_bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-beenhere" /></template>
<style>
.fmoxa2_bw {
  fill: currentColor;
  d: path("M19 1H5c-1.1 0-1.99.9-1.99 2L3 15.93c0 .69.35 1.3.88 1.66L12 23l8.11-5.41c.53-.36.88-.97.88-1.66L21 3c0-1.1-.9-2-2-2m-7 19.6l-7-4.66V3h14v12.93zm-2.01-7.42l-2.58-2.59L6 12l4 4l8-8l-1.42-1.42z");
}

.p9p3kgbme {
  fill: currentColor;
  d: path("M19 3H5v12.93l7 4.66l7-4.67zm-9 13l-4-4l1.41-1.41l2.58 2.58l6.59-6.59L18 8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
