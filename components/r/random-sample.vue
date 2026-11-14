<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eum3ahblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:random-sample" /></template>
<style>
.eum3ahblk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.309 2.461l13.523 3.623a1 1 0 0 1 .707 1.225l-3.623 13.523a1 1 0 0 1-1.225.707L3.168 17.916a1 1 0 0 1-.707-1.225L6.084 3.168a1 1 0 0 1 1.225-.707Zm1.863 4.64h.01M12 12h.01m2.818 4.899h.01");
}

</style>
