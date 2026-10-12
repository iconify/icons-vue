<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me4egdcvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tongue-depressor-sharp" /></template>
<style>
.me4egdcvt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.26 13.76l10.5-10.5a1.75 1.75 0 0 1 2.48 2.48l-10.5 10.5a1.75 1.75 0 0 1-2.48-2.48Zm9.49-.26h8.5m-7.25 0v3a3 3 0 0 0 6 0v-3m-3 0V16");
}

</style>
