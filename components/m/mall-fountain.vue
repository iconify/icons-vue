<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwvu1lrxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mall-fountain" /></template>
<style>
.qwvu1lrxv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 17h17L19 20.5H5Zm8.5 0V9m0 0c-3 0-4.5 2-5 4m5-4c3 0 4.5 2 5 4m-5-9.5v2M8.5 6h.01m6.99 0h.01");
}

</style>
