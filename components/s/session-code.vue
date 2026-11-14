<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwc1i4b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:session-code" /></template>
<style>
.qwc1i4b0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.875 3h10.25A4.375 4.375 0 0 1 21.5 7.375v4.75a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 12.125v-4.75A4.375 4.375 0 0 1 6.875 3M12 16.5v4m-4.5 0h9M6.75 9.75h.01m3.49 0h.01m3.49 0h.01m3.49 0h.01");
}

</style>
