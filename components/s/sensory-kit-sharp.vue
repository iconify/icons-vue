<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="piqi14a9o"/><path class="cwg9rpbau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sensory-kit-sharp" /></template>
<style>
.cwg9rpbau {
  d: path("m12.14 11.32l.83 1.82l.15.32l.34.04l2 .22l.34.04l-.25.24l-1.48 1.35l-.26.24l.07.34l.4 1.96l.07.35l-.3-.18l-1.75-.99l-.3-.17l-.3.17l-1.75.99l-.3.18l.07-.35l.4-1.96l.07-.34l-.26-.24L8.45 14l-.25-.24l.34-.04l2-.22l.34-.04l.15-.32l.83-1.82L12 11z");
}

.piqi14a9o {
  d: path("M2.75 8.25h18.5v13H2.75zm6 0V4.5h6.5v3.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
