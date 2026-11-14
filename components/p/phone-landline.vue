<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="othe0-b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:phone-landline" /></template>
<style>
.othe0-b3t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8V6.5C3 4.5 7 3 12 3s9 1.5 9 3.5V8h-4.5V6.5h-9V8Zm1.5 3h15v10.5h-15Zm4 3.5h.01m3.49 0h.01m3.49 0h.01M8.5 17.75h.01m3.49 0h.01m3.49 0h.01");
}

</style>
