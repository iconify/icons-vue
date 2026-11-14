<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m3p6w7_tn"/><path class="daql9fbbp"/><path class="soys148ph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:route-one-way-trip" /></template>
<style>
.daql9fbbp {
  d: path("M8 18.5h7a3.5 3.5 0 0 0 0-7H9a3.5 3.5 0 0 1 0-7h11");
}

.m3p6w7_tn {
  d: path("M3 18.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.soys148ph {
  d: path("M17.5 2L20 4.5L17.5 7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
