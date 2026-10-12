<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfvjvlb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:studio-light-sharp" /></template>
<style>
.rfvjvlb_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h12v8h-12zm3.5 2.75V11m3-2.5V11m5.5-5.25l6.5-3m-6.5 11l6.5 3m-12.5-3v7.5m-3.75 0h7.5");
}

</style>
