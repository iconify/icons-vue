<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rnpjchqpt"/><path class="zfr_eljkq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:service-animal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rnpjchqpt {
  d: path("M5.5 20.65V18.1q0-.6.32-1.11l1.86-2.98q.32-.51.77-.91l3.6-3.2q.45-.4.57-.99l.51-2.57q.12-.59.37-1.14l.75-1.65q.25-.55.71-.17l.58.49q.46.38 1.02.59l3.63 1.33q.56.21.49.81l-.11.8q-.07.6-.66.7l-1.82.3q-.59.1-.63.7l-.17 2.8q-.04.6-.02 1.2l.21 7.55q.02.6-.58.6h-1.3q-.6 0-.64-.6l-.17-3.05q-.04-.6-.49-.2l-1.35 1.2q-.45.4-.45 1v1.05q0 .6-.6.6H6.1q-.6 0-.6-.6");
}

.zfr_eljkq {
  d: path("M5.75 19.5c-1.75 0-3 .75-3 1.75m11-8.75v3m-1.5-1.5h3");
}

</style>
