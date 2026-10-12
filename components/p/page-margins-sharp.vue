<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ohxdrbbbi"/><path class="blwzqqbdp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:page-margins-sharp" /></template>
<style>
.blwzqqbdp {
  d: path("M7.75 9V6.75H10m4 0h2.25V9m0 6v2.25H14m-4 0H7.75V15");
}

.ohxdrbbbi {
  d: path("M3.75 2.75h16.5v18.5H3.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
