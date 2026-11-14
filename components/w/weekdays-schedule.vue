<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to0yleyzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:weekdays-schedule" /></template>
<style>
.to0yleyzx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5h19V21h-19Zm5.5-2v4m8-4v4m-10.5 7h.01m3.24 0h.01m3.24 0h.01m3.24 0h.01m3.24 0h.01");
}

</style>
