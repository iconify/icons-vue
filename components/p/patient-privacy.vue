<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lu7wvnb9y"/><path class="ck74srbyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:patient-privacy" /></template>
<style>
.ck74srbyc {
  d: path("M7 7c-.5 3.5.5 7 0 11m3.75-11c-.5 3.5.5 7 0 11");
}

.lu7wvnb9y {
  d: path("M3 5.5v14q2.25 1.875 4.5 0q2.25 1.875 4.5 0c1 .75 1.75.75 2.5.25L14 5.5M2.5 3h19M4 4.5h.01m4.49 0h.01m4.49 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
