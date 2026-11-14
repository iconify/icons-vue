<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="luj2gsbkv"/><path class="r5r1u_w0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vlog" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.luj2gsbkv {
  d: path("M6 6.5h6a3.5 3.5 0 0 1 3.5 3.5v5a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 15v-5A3.5 3.5 0 0 1 6 6.5");
}

.r5r1u_w0d {
  d: path("m16.379 7.1l2.5-1.136A1.5 1.5 0 0 1 21 7.33v5.706a1.5 1.5 0 0 1-1.895 1.447l-2.5-.682a1.5 1.5 0 0 1-1.105-1.447V8.466a1.5 1.5 0 0 1 .879-1.366M6 12.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
