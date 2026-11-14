<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xtgjheb0e"/><path class="jspj_mkpy"/><path class="v9j119bcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:marine-compass" /></template>
<style>
.jspj_mkpy {
  d: path("M6 13.25a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v9j119bcq {
  d: path("m10.5 7.25l1.5-2.5l1.5 2.5Zm4.941 1.085l-1.803 6.062l-5.079 3.768l1.803-6.062Z");
}

.xtgjheb0e {
  d: path("M5 2.5h14A2.5 2.5 0 0 1 21.5 5v14a2.5 2.5 0 0 1-2.5 2.5H5A2.5 2.5 0 0 1 2.5 19V5A2.5 2.5 0 0 1 5 2.5Z");
}

</style>
