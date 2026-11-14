<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="txncksb1k"/><path class="xjbdayfcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:travel-medical-abroad" /></template>
<style>
.txncksb1k {
  d: path("M2.5 9.25a6.75 6.75 0 1 0 13.5 0a6.75 6.75 0 1 0-13.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xjbdayfcd {
  d: path("M6.25 9.25a3 6.75 0 1 0 6 0a3 6.75 0 1 0-6 0Zm-3.75 0H16M18 15v6m-3-3h6");
}

</style>
