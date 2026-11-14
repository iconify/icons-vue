<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhbdpacgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:piracy" /></template>
<style>
.fhbdpacgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 14v-1.25a5.5 5.5 0 1 1 5.5 0V14ZM5 15.5L19 21m0-5.5L5 21M9.75 8.75h.01m4.49 0h.01");
}

</style>
