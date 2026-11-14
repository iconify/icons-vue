<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syqk2ehya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mission-control" /></template>
<style>
.syqk2ehya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5.75h4.25v6.5H2.5Zm7-1.5h5v8h-5Zm7.75 1.5h4.25v6.5h-4.25ZM2.5 15.25h19v4.5h-19Zm9.5-3v3");
}

</style>
