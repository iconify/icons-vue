<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzg_wvbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:standup-bot" /></template>
<style>
.tzg_wvbsg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5H14V21H2.5Zm13-6a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2V7a2 2 0 0 1-2 2H18l-2.5 2Zm-7.25 6V8m0-2.75h.01M5.75 15.5h.01m4.99 0h.01");
}

</style>
