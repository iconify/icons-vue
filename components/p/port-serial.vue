<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on-l58bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:port-serial" /></template>
<style>
.on-l58bfg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.772 7.5h10.456a2.625 2.625 0 0 1 2.562 3.194l-.833 3.75a2.625 2.625 0 0 1-2.563 2.056H7.606a2.625 2.625 0 0 1-2.563-2.056l-.833-3.75A2.625 2.625 0 0 1 6.772 7.5m.728 3h.01m2.99 0h.01m2.99 0h.01m2.99 0h.01M9 13.5h.01m2.99 0h.01m2.99 0h.01");
}

</style>
