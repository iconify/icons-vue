<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zkf5f4bpj"/><path class="fjhpxzbfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mountains-broken" /></template>
<style>
.fjhpxzbfq {
  d: path("M5.80664 8.21261C7.30664 9.71261 8.50664 9.61261 9.40664 8.61261C10.3066 7.61251 11.4066 8.51251 12.5066 8.11261");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zkf5f4bpj {
  d: path("M7.26333 19.7125H5.80833C2.80833 19.7125 1.90833 18.2125 3.00833 15.4125L6.10833 7.21248C7.60833 3.31248 10.7083 3.31248 12.2083 7.21248L13.0083 9.31248C13.6083 10.8125 14.6083 10.8125 15.3083 9.41248C16.4083 7.31248 18.5083 7.41248 19.5083 10.1125L21.1083 15.5125C22.0083 18.2125 21.1083 19.7125 18.2083 19.7125H12.0083H10.8633");
}

</style>
