<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="agu0vivvz"/><circle class="taq4_hb2a"/><path class="f4pqbwbcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:santa-hat-sharp" /></template>
<style>
.agu0vivvz {
  d: path("m4.92 15.06l1.66-5.62L7 8l1.17-.94l2.66-2.12L12 4l1.47.28l1.06.19l1.47.28l.72 1.32l1.35 4.05l-2.243.814L17.02 13l-.42 2.5l-.1 1h-12z");
}

.f4pqbwbcg {
  d: path("M2.75 16.5h16.5v4.75H2.75z");
}

.taq4_hb2a {
  cx: 18.75px;
  cy: 12px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
