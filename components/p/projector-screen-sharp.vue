<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="n0r_n9bap"/><circle class="f--yjl04t"/><path class="kocvjibha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:projector-screen-sharp" /></template>
<style>
.f--yjl04t {
  cx: 15.75px;
  cy: 12.25px;
  r: 2.75px;
}

.kocvjibha {
  d: path("M6.25 10.75h3.5m-3.5 3h3.5m-3.25 4v2.5m11-2.5v2.5");
}

.n0r_n9bap {
  d: path("M2.75 6.75h18.5v11H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
