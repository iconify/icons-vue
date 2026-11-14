<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml3445_ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vr-headset-lock" /></template>
<style>
.ml3445_ri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3.5h9A2.5 2.5 0 0 1 19 6v3.5a2.5 2.5 0 0 1-2.5 2.5h-2a2.5 2.5 0 0 0-5 0h-2A2.5 2.5 0 0 1 5 9.5V6a2.5 2.5 0 0 1 2.5-2.5Zm-5 4.25H5m14 0h2.5M15 17.5h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

</style>
