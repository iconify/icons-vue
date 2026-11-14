<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxpzqkbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pedals" /></template>
<style>
.sxpzqkbyj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.172 9.612l3.913-.831l1.871 8.803l-3.912.832Zm6.916 1.957l3.913-.832l1.455 6.847l-3.912.832Zm5.149-6.358l3.912-.832l2.807 13.205l-3.912.832ZM2.5 21h19");
}

</style>
