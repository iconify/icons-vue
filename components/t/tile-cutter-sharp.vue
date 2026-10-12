<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gch0uibuy"/><path class="ieqebqbbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tile-cutter-sharp" /></template>
<style>
.gch0uibuy {
  d: path("M2.75 16.5h18.5v4.75H2.75zm1 0V7.25H9.5m4.5 0h6.25v9.25m-7.75-11l4-2.75m-7 2.75H14V9H9.5z");
}

.ieqebqbbe {
  d: path("M6.75 13.5h10.5v3H6.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
