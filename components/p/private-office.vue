<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dxsxh5xhc"/><path class="qlcgfrd9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:private-office" /></template>
<style>
.dxsxh5xhc {
  d: path("M6 2.5h12v19H6Z");
}

.qlcgfrd9t {
  d: path("M9 5.5h6V8H9Zm6 7.5h.01M3 21.5h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
