<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="vfcwvdbfr"/><path class="e2xpizbqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sensory-kit" /></template>
<style>
.e2xpizbqh {
  d: path("M8.75 8.25V6.5a2 2 0 0 1 2-2h2.5a2 2 0 0 1 2 2v1.75m-3.11 3.07l.83 1.82q.15.32.49.36l2 .22q.34.04.09.28l-1.48 1.35q-.26.24-.19.58l.4 1.96q.07.35-.23.17l-1.75-.99q-.3-.17-.6 0l-1.75.99q-.3.18-.23-.17l.4-1.96q.07-.34-.19-.58L8.45 14q-.25-.24.09-.28l2-.22q.34-.04.49-.36l.83-1.82q.14-.32.28 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vfcwvdbfr {
  width: 18.5px;
  height: 13px;
  x: 2.75px;
  y: 8.25px;
  rx: 2.5px;
}

</style>
