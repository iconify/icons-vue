<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hhr-5syjo"/><path class="zp7yt03sc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:text-color-fill" /></template>
<style>
.hhr-5syjo {
  d: path("M3.5 3h17v13h-17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zp7yt03sc {
  d: path("m8 13l4-7.25L16 13m-6.5-2.5h5m-11 8h17V21h-17Z");
}

</style>
