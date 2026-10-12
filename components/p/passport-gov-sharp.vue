<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l5g864bjc"/><path class="w_6rpybie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:passport-gov-sharp" /></template>
<style>
.l5g864bjc {
  d: path("M5.25 2.75h13.5v18.5H5.25z");
}

.w_6rpybie {
  d: path("m12.14 6.57l.82 1.84l.15.32l.34.04l2.01.21l.34.03l-.26.24l-1.49 1.35l-.26.23l.07.34l.42 1.97l.07.35l-.3-.18l-1.75-1.01l-.3-.17l-.3.17l-1.75 1.01l-.3.18l.07-.35l.42-1.97l.07-.34l-.26-.23l-1.49-1.35l-.26-.24l.34-.03l2.01-.21l.34-.04l.15-.32l.82-1.84l.14-.32zM9.25 17.25h5.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
