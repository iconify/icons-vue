<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p9fct0o_n"/><path class="bqge78l4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:oven-open" /></template>
<style>
.bqge78l4j {
  d: path("M7 11.5h10v3.25H7Z");
}

.p9fct0o_n {
  d: path("M3.5 3h17v14.5h-17Zm0 14.5h17l1 3h-19Zm0-9h17M7.25 5.75h.01m2.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
