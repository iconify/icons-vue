<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uix2_zizn"/><path class="gf7mw6bxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smile-practice" /></template>
<style>
.gf7mw6bxe {
  d: path("M6.5 15.25q4 4.75 8 0M19.25 2q0 2.75 2.75 2.75q-2.75 0-2.75 2.75q0-2.75-2.75-2.75q2.75 0 2.75-2.75Z");
}

.uix2_zizn {
  d: path("M2.75 13.75a7.75 7.75 0 1 0 15.5 0a7.75 7.75 0 1 0-15.5 0ZM8 12h.01M13 12h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
