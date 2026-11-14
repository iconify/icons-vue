<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="psagppbwa"/><path class="ob4_rfqwi"/><path class="jtmw-hvob"/><path class="oh419w-xl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shade-guide" /></template>
<style>
.jtmw-hvob {
  d: path("m13.575 5.009l2.923.674l-2.137 9.257l-2.923-.675Z");
}

.ob4_rfqwi {
  d: path("m7.502 5.683l2.923-.674l2.137 9.256l-2.923.675Z");
}

.oh419w-xl {
  d: path("m19.129 6.938l2.364 1.847l-5.848 7.486l-2.364-1.847ZM10.5 18.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.psagppbwa {
  d: path("m2.507 8.785l2.364-1.847l5.848 7.486l-2.364 1.847Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
