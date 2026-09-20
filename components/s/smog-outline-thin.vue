<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u-pn1xbtk"/><path class="n-7t0yb1r"/><path class="mwg9vvb9j"/><path class="ceaqndb6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:smog-outline-thin" /></template>
<style>
.ceaqndb6y {
  d: path("M14 21v-4h4v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mwg9vvb9j {
  d: path("M7 21v-5h4v5");
}

.n-7t0yb1r {
  d: path("M3 13h18");
}

.u-pn1xbtk {
  d: path("M8 7a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
