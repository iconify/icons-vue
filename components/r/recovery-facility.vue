<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f4e-m9bgv"/><path class="ky2f7t9jd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:recovery-facility" /></template>
<style>
.f4e-m9bgv {
  d: path("M9.034 18H2.5V9l4 2.5V9l4 2.5v-9h3v11.066m4-.066a4 4 0 1 1-4 4");
}

.ky2f7t9jd {
  d: path("m11.75 19.25l1.75-1.75l1.75 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
