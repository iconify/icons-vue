<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q9c73nx4c"/><path class="ir1fu7k4o"/><path class="cid3i0bxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-lien" /></template>
<style>
.cid3i0bxr {
  d: path("m15.995 16.884l3.889-3.889l2.121 2.121l-3.889 3.889Z");
}

.ir1fu7k4o {
  d: path("M16 7V4h2v4.75m-5.005 11.134l3.889-3.889l2.121 2.121l-3.889 3.889Z");
}

.q9c73nx4c {
  d: path("M9.66 20.5H4v-10l8-7l7.127 6.236");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
