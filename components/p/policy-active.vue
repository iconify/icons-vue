<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c__8zrb-l"/><path class="yhk3zcbmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:policy-active" /></template>
<style>
.c__8zrb-l {
  d: path("M14.278 21.5H5v-19h8.5L19 8v5.822");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yhk3zcbmd {
  d: path("M13.5 2.5V8H19M8.5 12h7m-7 4h3m3.25 2l2 2L21 15.75");
}

</style>
