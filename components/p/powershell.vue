<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vbnspjbps"/><path class="cl2jnacbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:powershell" /></template>
<style>
.cl2jnacbi {
  d: path("m7.5 8.5l4 3.5l-4 3.5m5 0h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vbnspjbps {
  d: path("M7.179 4h11.658a2.625 2.625 0 0 1 2.58 3.109l-2.016 10.75A2.625 2.625 0 0 1 16.821 20H5.163a2.625 2.625 0 0 1-2.58-3.109l2.016-10.75A2.625 2.625 0 0 1 7.179 4");
}

</style>
