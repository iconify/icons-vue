<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jyj93sono"/><path class="jr_icmb2j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:popup-container-store" /></template>
<style>
.jr_icmb2j {
  d: path("M13.75 8.5h5V19h-5ZM2.5 21.5h19");
}

.jyj93sono {
  d: path("M2.5 5.5h19V19h-19Zm3 2.5v8.5M8.25 8v8.5M11 8v8.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
