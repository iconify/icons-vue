<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="esjpohbje"/><path class="vcx_nmbxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spread-operator" /></template>
<style>
.esjpohbje {
  d: path("M6.5 3.5h-3v17h3m11-17h3v17h-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vcx_nmbxn {
  fill: currentColor;
  d: path("M7 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm4 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm4 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

</style>
