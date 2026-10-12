<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nmv32cbob"/><circle class="yyexh0zlp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:table-tennis" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nmv32cbob {
  d: path("M2.75 13h18.5M5 13v8.25M19 13v8.25m-7-11.5V13");
}

.yyexh0zlp {
  cx: 16.5px;
  cy: 6.5px;
  r: 1.75px;
}

</style>
