<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cwg415b1b"/><path class="fvcmg4cim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:statement-signature-card" /></template>
<style>
.cwg415b1b {
  d: path("M2.5 5h19v14h-19Zm3 10.5h13");
}

.fvcmg4cim {
  d: path("M6 12.5c1-3.5 2.5-4 3-2s1 2.25 2 0s2-1.5 2.5.5c.5 1.5 2 1 3.5-.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
