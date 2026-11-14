<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m0jwnbckb"/><path class="gq5igqbpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:veranda" /></template>
<style>
.gq5igqbpf {
  d: path("M4 5.5v16m8-14v14m8-12v12M2.5 17h19");
}

.m0jwnbckb {
  fill: currentColor;
  d: path("m2.5 3l19 4.75v2L2.5 5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
