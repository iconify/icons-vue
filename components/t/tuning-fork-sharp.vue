<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xevli_xvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tuning-fork-sharp" /></template>
<style>
.xevli_xvp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.75v7.5a3.5 3.5 0 0 0 7 0v-7.5m-3.5 11v7.5M4.5 4.5l-1.875 3l1.875 3m15-6l1.875 3l-1.875 3");
}

</style>
