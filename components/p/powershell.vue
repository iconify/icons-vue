<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e4hybsb_w"/><path class="cl2jnacbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:powershell" /></template>
<style>
.cl2jnacbi {
  d: path("m7.5 8.5l4 3.5l-4 3.5m5 0h3");
}

.e4hybsb_w {
  d: path("M5 4h17l-3 16H2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
