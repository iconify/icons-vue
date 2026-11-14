<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j80v9wb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vr-headset-alert" /></template>
<style>
.j80v9wb3p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3.5h13A2.5 2.5 0 0 1 21 6v2.5a2.5 2.5 0 0 1-2.5 2.5H15a3 3 0 0 0-6 0H5.5A2.5 2.5 0 0 1 3 8.5V6a2.5 2.5 0 0 1 2.5-2.5ZM18 13.75l4 7.75h-8Zm0 3v1.5M18 20h.01");
}

</style>
