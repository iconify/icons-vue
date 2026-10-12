<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e5l-tj9-m"/><path class="ltvxn310f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pipe-wrench" /></template>
<style>
.e5l-tj9-m {
  d: path("m16.42 2.81l3.18 3.18l-5.66 5.66m2.13-2.12L13.24 6.7m-1.42 7.07l-1.41 1.41m0 0zq1.06 1.06 0 2.12l-2.83 2.83q-1.06 1.06-2.12 0t0-2.12l2.83-2.83q1.06-1.06 2.12 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ltvxn310f {
  d: path("m13.06 10.76l1.77 1.77q.53.53 0 1.06l-1.06 1.06q-.53.53-1.06 0l-1.77-1.77q-.53-.53 0-1.06L12 10.76q.53-.53 1.06 0");
}

</style>
