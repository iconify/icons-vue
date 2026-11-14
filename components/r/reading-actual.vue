<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k_2h91g8y"/><path class="pmz62zbci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reading-actual" /></template>
<style>
.k_2h91g8y {
  d: path("M6 19a8.5 8.5 0 1 1 12 0m-6-6l3.5-3.5");
}

.pmz62zbci {
  d: path("M13 9.5h2.5V12ZM12 13h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
