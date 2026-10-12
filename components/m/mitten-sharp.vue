<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysmfpnbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mitten-sharp" /></template>
<style>
.ysmfpnbeq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 15.25v-7a4.75 4.75 0 0 1 9.5 0V10l1.6-1.6a1.6 1.6 0 0 1 2.3 2.25l-3.9 4v.6Zm-.75 0h11v6h-11z");
}

</style>
