<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nmv32cbob"/><circle class="yyexh0zlp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:table-tennis-sharp" /></template>
<style>
.nmv32cbob {
  d: path("M2.75 13h18.5M5 13v8.25M19 13v8.25m-7-11.5V13");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yyexh0zlp {
  cx: 16.5px;
  cy: 6.5px;
  r: 1.75px;
}

</style>
