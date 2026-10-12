<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lkmcuhqvz"/><path class="c2qfa_8wo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reward-model" /></template>
<style>
.c2qfa_8wo {
  d: path("M6.25 17.75v-2m2.25 2v-4m2.25 4v-6m6.14-8.63l.99 2.21q.14.32.49.36l2.41.25q.34.04.08.27l-1.8 1.62q-.26.24-.18.58l.5 2.37q.07.34-.23.17l-2.1-1.21q-.3-.18-.6 0l-2.1 1.21q-.3.17-.23-.17l.5-2.37q.08-.34-.18-.58l-1.8-1.62q-.26-.23.08-.27l2.41-.25q.35-.04.49-.36l.99-2.21q.14-.32.28 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lkmcuhqvz {
  width: 11.5px;
  height: 12.5px;
  x: 2.75px;
  y: 8.75px;
  rx: 2.5px;
}

</style>
