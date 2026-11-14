<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sv1v2-bzd"/><path class="u43iprb9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rocket-search" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sv1v2-bzd {
  d: path("m18.332 5.2l-.408 2.529a1.75 1.75 0 0 1-.49.959l-4.727 4.726a1.75 1.75 0 0 1-2.475 0l-2.121-2.121a1.75 1.75 0 0 1 0-2.475l4.726-4.726a1.75 1.75 0 0 1 .959-.491l2.529-.408A1.75 1.75 0 0 1 18.332 5.2");
}

.u43iprb9g {
  d: path("M9.702 7.227H5.813L3.161 9.879l3.712.176m7.425 1.768v1.8m-1.846 3.935l-.806.806l-.176-3.712m-4.066-.531l-1.768 1.768M15.25 17.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

</style>
