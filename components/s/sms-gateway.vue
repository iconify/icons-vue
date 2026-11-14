<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivod19m-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sms-gateway" /></template>
<style>
.ivod19m-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 4.5a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2V7a2 2 0 0 1-2 2h-7.5l-3 1.75V9H6a2 2 0 0 1-2-2Zm0 9h16v8H4Zm0 4h16m-6.5-2h3m-3 4h3");
}

</style>
