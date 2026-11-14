<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vka5bvrxb"/><path class="os6wtv_yb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:workflow-automation" /></template>
<style>
.os6wtv_yb {
  d: path("m9.75 15.25l2 2l-2 2M18.5 2.5l-4 5.5h2.75L16 12l4.5-5.75h-2.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vka5bvrxb {
  d: path("M3 3.5h6.5V10H3ZM14.5 14H21v6.5h-6.5Zm-8.25-4v5.25a2 2 0 0 0 2 2h3.25");
}

</style>
