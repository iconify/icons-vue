<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ipyx0wwka"/><path class="tce0vmi_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:monitor-crt" /></template>
<style>
.ipyx0wwka {
  d: path("M4 5c0-1.25 1-2 2-2h12c1 0 2 .75 2 2v10.5c0 2-1 3-2.5 3h-11c-1.5 0-2.5-1-2.5-3Zm3 16h10");
}

.tce0vmi_q {
  d: path("M7 6.5h10v8H7ZM17 13h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
