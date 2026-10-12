<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="u_uki-bck"/><path class="qjpekzb1q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:passport-gov" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qjpekzb1q {
  d: path("m12.14 6.57l.82 1.84q.15.32.49.36l2.01.21q.34.03.08.27l-1.49 1.35q-.26.23-.19.57l.42 1.97q.07.35-.23.17L12.3 12.3q-.3-.17-.6 0l-1.75 1.01q-.3.18-.23-.17l.42-1.97q.07-.34-.19-.57L8.46 9.25q-.26-.24.08-.27l2.01-.21q.34-.04.49-.36l.82-1.84q.14-.32.28 0M9.25 17.25h5.5");
}

.u_uki-bck {
  width: 13.5px;
  height: 18.5px;
  x: 5.25px;
  y: 2.75px;
  rx: 2px;
}

</style>
