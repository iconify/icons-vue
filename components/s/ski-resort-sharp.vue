<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lgq6un4_t"/><path class="cvx864bpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ski-resort-sharp" /></template>
<style>
.cvx864bpd {
  d: path("m6.75 9.5l1.75 1.25l1.5-1.5l1.75 1.5M8 21.25l8-3.5m-8 0l8 3.5");
}

.lgq6un4_t {
  d: path("m3.37 14.17l5.51-9.59l.62-1.08l.64 1.07l2.47 4.11l.64 1.07l.74-1.01l.52-.73l.74-1.01l.74 1.01l4.52 6.23l.74 1.01H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
