<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h0yojpbyp"/><path class="fvv73ib0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:timer-check" /></template>
<style>
.fvv73ib0o {
  d: path("M8.75 13.25L11 15.5l4.25-4.25");
}

.h0yojpbyp {
  d: path("M4 13a8 8 0 1 0 16 0a8 8 0 1 0-16 0ZM9.5 2.5h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
