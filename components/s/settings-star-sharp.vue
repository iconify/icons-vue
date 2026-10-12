<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)"><path class="i9zy-22rr"/></g><path class="go6cdpb0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:settings-star-sharp" /></template>
<style>
.c7atyebze {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.go6cdpb0v {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.54 13.92l.83 1.82l.15.32l.34.04l2 .22l.34.04l-.25.24l-1.48 1.35l-.26.24l.07.34l.4 1.96l.07.35l-.3-.18l-1.75-.99l-.3-.17l-.3.17l-1.75.99l-.3.18l.07-.35l.4-1.96l.07-.34l-.26-.24l-1.48-1.35l-.25-.24l.34-.04l2-.22l.34-.04l.15-.32l.83-1.82l.14-.32z");
}

.i9zy-22rr {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.36 4.57l.1-.96l.07-.74h2.94l.07.74l.1.96l.07.74l.69.29l.43.18l.69.29l.58-.48l.74-.61l.58-.48l.53.53l1.02 1.02l.53.53l-.48.58l-.61.74l-.48.58l.29.69l.18.43l.29.69l.74.07l.96.1l.74.07v2.94l-.74.07l-.96.1l-.74.07l-.29.69l-.18.43l-.29.69l.48.58l.61.74l.48.58l-.53.53l-1.02 1.02l-.53.53l-.58-.48l-.74-.61l-.58-.48l-.69.29l-.43.18l-.69.29l-.07.74l-.1.96l-.07.74h-2.94l-.07-.74l-.1-.96l-.07-.74l-.69-.29l-.43-.18l-.69-.29l-.58.48l-.74.61l-.58.48l-.53-.53l-1.02-1.02l-.53-.53l.48-.58l.61-.74l.48-.58l-.29-.69l-.18-.43l-.29-.69l-.74-.07l-.96-.1l-.74-.07v-2.94l.74-.07l.96-.1l.74-.07l.29-.69l.18-.43l.29-.69l-.48-.58l-.61-.74l-.48-.58l.53-.53l1.02-1.02l.53-.53l.58.48l.74.61l.58.48l.69-.29l.43-.18l.69-.29z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.utmrllbfo {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
  fill: var(--svg-color--000, #000);
}

</style>
