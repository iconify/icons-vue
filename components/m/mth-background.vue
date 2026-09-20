<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ey1b-gbmn"/><path class="iue5q1_to"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mth-background" /></template>
<style>
.ey1b-gbmn {
  fill: var(--svg-color--0072ff, #0072ff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.iue5q1_to {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.705 15.2L12.5 17v-5.24c0-.875.49-1.725 1.165-2.25L15.5 8v4.98c0 .86-.14 1.7-.795 2.225zm-5.415.005c-.655-.525-.79-1.365-.79-2.225V8l1.835 1.51a3.12 3.12 0 0 1 1.165 2.25V17zm9.57 2.685L17 19.5v-11c0-.915.235-1.81.95-2.38L20 4.5v11.01a3.05 3.05 0 0 1-1.14 2.38m-13.72 0A3.05 3.05 0 0 1 4 15.51V4.5l2.05 1.625C6.76 6.69 7 7.585 7 8.5v11z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
