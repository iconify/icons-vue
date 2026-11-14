<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u9wuy_bfq"/><path class="iflxnubtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sale-ribbon" /></template>
<style>
.iflxnubtr {
  d: path("m9 14.5l-2 7l5-3l5 3l-2-7");
}

.u9wuy_bfq {
  d: path("m12 2.75l3.5 1V12a3.5 3.5 0 0 1-7 0V3.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
