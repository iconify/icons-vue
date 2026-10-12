<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="egredsbnr"/><path class="kj3cfzxdw"/><path class="bs4o24bpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:time-capsule-sharp" /></template>
<style>
.bs4o24bpy {
  d: path("M15.75 11v1h.75");
}

.egredsbnr {
  d: path("M2.75 6.5h18.5v11H2.75zm7.25 0v11");
}

.kj3cfzxdw {
  d: path("M13 12a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
