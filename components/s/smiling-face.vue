<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="r1bq7qb_u"/><circle class="a6uxc0blr"/><circle class="djz8f828d"/><path class="b3x59l2bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:smiling-face" /></template>
<style>
.a6uxc0blr {
  cx: 20.5px;
  cy: 24.592px;
  r: 5px;
  fill: currentColor;
}

.b3x59l2bo {
  fill: currentColor;
  d: path("M48.11 37.02c-4.328 6.107-9.451 7.644-16.111 7.644c-6.659 0-11.782-1.536-16.11-7.644c-.603-.85-2.19-.315-1.839.919c2.273 8.005 10 12.667 17.95 12.667s15.678-4.662 17.951-12.667c.349-1.235-1.238-1.769-1.841-.919");
}

.djz8f828d {
  cx: 43.5px;
  cy: 24.592px;
  r: 5px;
  fill: currentColor;
}

.r1bq7qb_u {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 57.5C16.836 59.5 4.5 47.164 4.5 32S16.836 4.5 32 4.5S59.5 16.836 59.5 32S47.163 59.5 32 59.5");
}

</style>
