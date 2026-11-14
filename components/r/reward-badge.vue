<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="op4vu5bde"/><path class="vtk3i1brc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reward-badge" /></template>
<style>
.op4vu5bde {
  d: path("m12 2.25l2.135 1.781l2.74-.475l.959 2.61l2.61.959l-.475 2.74L21.75 12l-1.781 2.135l.475 2.74l-2.61.959l-.959 2.61l-2.74-.475L12 21.75l-2.135-1.781l-2.74.475l-.959-2.61l-2.61-.959l.475-2.74L2.25 12l1.781-2.135l-.475-2.74l2.61-.959l.959-2.61l2.74.475Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vtk3i1brc {
  d: path("M13.75 10.25C13.5 9.5 12.9 9 12 9c-1.05 0-1.75.6-1.75 1.5c0 1.6 3.5.9 3.5 3c0 .9-.75 1.5-1.75 1.5c-.9 0-1.55-.4-1.75-1M12 7.75V9m0 6v1.25");
}

</style>
