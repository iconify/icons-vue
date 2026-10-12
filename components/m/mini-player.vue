<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="er24pvfje"/><rect class="f954nnbll"/><path class="ick5ncbta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mini-player" /></template>
<style>
.er24pvfje {
  d: path("m3.75 3.75l5 5m0-4v4h-4");
}

.f954nnbll {
  width: 10px;
  height: 9px;
  x: 11.25px;
  y: 11.25px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ick5ncbta {
  d: path("m15.26 14.06l2.23 1.38q.51.31 0 .62l-2.23 1.38q-.51.31-.51-.29v-2.8q0-.6.51-.29");
}

</style>
