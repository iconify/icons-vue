<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jss5sobca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:widget-resize" /></template>
<style>
.jss5sobca {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5H18V18H2.5Zm0 6H18M7.5 4.25h.01m2.74 0h.01m2.74 0h.01M7.5 6.75h.01m2.74 0h.01m2.74 0h.01m.49 6.75l8 8m-4.75 0h4.75v-4.75");
}

</style>
