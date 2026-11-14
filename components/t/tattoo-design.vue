<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="js-122smr"/><path class="bhb-_wber"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tattoo-design" /></template>
<style>
.bhb-_wber {
  d: path("m12.707 9.172l2.121 2.121l-4.949 4.95l-2.122-2.122Zm-4.95 4.949l2.122 2.122l-2.829.707ZM7.05 16.95l-1.768 1.768M3.25 20.75h.01");
}

.js-122smr {
  d: path("m16.95 2.808l4.242 4.242l-5.303 5.304l-4.243-4.243Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
