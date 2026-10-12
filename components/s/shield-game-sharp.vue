<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m1k7cdbiv"/><path class="sw15fphve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shield-game-sharp" /></template>
<style>
.m1k7cdbiv {
  d: path("M5.75 3h14v8c0 5-3.5 8.5-7.75 10.25C7.75 19.5 4.25 16 4.25 11V3z");
}

.sw15fphve {
  d: path("m12.14 7.57l.75 1.69l.14.32l.35.03l1.84.19l.35.04l-.26.24l-1.38 1.23l-.26.23l.08.35l.38 1.8l.07.34l-.3-.17l-1.6-.92l-.3-.18l-.3.18l-1.6.92l-.3.17l.07-.34l.38-1.8l.08-.35l-.26-.23l-1.38-1.23l-.26-.24l.35-.04l1.84-.19l.35-.03l.14-.32l.75-1.69l.14-.32z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
