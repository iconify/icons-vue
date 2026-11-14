<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxo4uacxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:oat-milk-latte" /></template>
<style>
.cxo4uacxp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h11v7.5a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm11 2h1a2.5 2.5 0 0 1 0 5h-1m4 4v7.5m-2.5-4L18 20l2.5-2.5m-5-3L18 17l2.5-2.5");
}

</style>
