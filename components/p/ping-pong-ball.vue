<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxbb6acle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ping-pong-ball" /></template>
<style>
.vxbb6acle {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM2.5 20h19m-19-10q3.5 7 6 7t3.5-3");
}

</style>
