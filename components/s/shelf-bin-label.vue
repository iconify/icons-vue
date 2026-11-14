<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i6d7m8l7a"/><path class="pw0mnab0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shelf-bin-label" /></template>
<style>
.i6d7m8l7a {
  d: path("M2.5 9H18v12.5H2.5Zm0 0L6 3.5h15.5L18 9m3.5-5.5V16L18 21.5");
}

.pw0mnab0x {
  d: path("M5 12.25h10.5v6H5Zm2.5 3H13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
