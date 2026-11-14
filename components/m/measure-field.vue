<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqbca1blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:measure-field" /></template>
<style>
.wqbca1blc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.461 16.136l-4.88 4.88l-4.597-4.597L16.419 2.984l4.597 4.597l-4.666 4.666M5.813 13.591l1.768 1.768m.707-4.243l1.131 1.132m1.344-3.607l1.767 1.768m.707-4.243l2.652 2.652M21 15h-5.75l3 3l-3 3H21");
}

</style>
