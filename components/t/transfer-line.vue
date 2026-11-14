<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="quxzo_a_a"/><path class="oxy9ir50k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:transfer-line" /></template>
<style>
.oxy9ir50k {
  d: path("m15 16.5l3 3l3-3");
}

.quxzo_a_a {
  d: path("M2.5 4.5h19m-19 15h19M6 4.5c0 8 12 5.5 12 15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
