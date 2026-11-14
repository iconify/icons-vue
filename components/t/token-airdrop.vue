<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrbcbgbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:token-airdrop" /></template>
<style>
.nrbcbgbrs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10a9 7.5 0 0 1 18 0Zm0 0l6 5m12-5l-6 5m-7 2.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4-1.25v2.5");
}

</style>
