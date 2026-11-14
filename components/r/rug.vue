<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ildy64tye"/><path class="suxfqkebb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rug" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ildy64tye {
  d: path("M9.082 7.5h8.586a1.75 1.75 0 0 1 1.566 2.533l-2.75 5.5a1.75 1.75 0 0 1-1.566.967H6.332a1.75 1.75 0 0 1-1.566-2.533l2.75-5.5A1.75 1.75 0 0 1 9.082 7.5");
}

.suxfqkebb {
  d: path("M10.677 10.25h3.366A1.21 1.21 0 0 1 15.125 12l-.46.921a1.5 1.5 0 0 1-1.342.829H9.957A1.21 1.21 0 0 1 8.875 12l.46-.921a1.5 1.5 0 0 1 1.342-.829M7.25 9H5.5m.25 3H4m.25 3H2.5m17.25-6h1.75m-3.25 3H20m-3.25 3h1.75");
}

</style>
