<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztwriye-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:temperature-fahrenheit" /></template>
<style>
.ztwriye-o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 13V5.25a2.75 2.75 0 0 1 5.5 0V13a4.25 4.25 0 1 1-5.5 0ZM7.5 9.5v6.75M13.75 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5 8.5V12h2.5m-2.5 4H21");
}

</style>
