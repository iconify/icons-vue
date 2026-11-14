<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yd6igib8b"/><path class="tpcgjfolm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:policy-addon" /></template>
<style>
.tpcgjfolm {
  d: path("M13.5 2.5V8H19M8.5 12h7m-7 4h3m6.5-1v6m-3-3h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yd6igib8b {
  d: path("M12.178 20.5H5v-18h8.5L19 8v4.222");
}

</style>
