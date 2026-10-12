<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-a44kpwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:safety-goggles-sharp" /></template>
<style>
.p-a44kpwc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8.5h12.5v7h-5L12 13.25L9.5 15.5h-5v-7zm3 0v2.25m4-2.25v2.25M2.75 12H4.5m15 0h1.75");
}

</style>
