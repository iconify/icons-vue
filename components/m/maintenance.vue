<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f1a4s5htp"/><path class="qn6st_bgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:maintenance" /></template>
<style>
.f1a4s5htp {
  d: path("M16.781 3.568a4.5 4.5 0 1 1-5.213 3.651");
}

.qn6st_bgv {
  d: path("m11.828 9.697l2.475 2.475l-8.131 8.131l-2.475-2.475Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
