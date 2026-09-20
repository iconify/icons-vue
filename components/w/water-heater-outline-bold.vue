<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k8sxdsbpq"/><path class="cfd43lbgp"/><path class="tfwtwzi0z"/><path class="uu00fhalg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:water-heater-outline-bold" /></template>
<style>
.cfd43lbgp {
  d: path("M7 13h10");
}

.k8sxdsbpq {
  d: path("M7 8a5 5 0 0 1 10 0v9a5 5 0 0 1 -10 0Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tfwtwzi0z {
  d: path("M3 5h5");
}

.uu00fhalg {
  d: path("M16 20h5");
}

</style>
