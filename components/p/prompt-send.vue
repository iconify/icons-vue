<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ydio1zd7h"/><path class="c_tqagbnx"/><circle class="ti2lvsb6o"/><path class="gyks0cbsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prompt-send" /></template>
<style>
.c_tqagbnx {
  d: path("M6.25 12h2");
}

.gyks0cbsy {
  d: path("M17.75 13.75V11m-1 1l1-1l1 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ti2lvsb6o {
  cx: 17.75px;
  cy: 12px;
  r: 3.5px;
}

.ydio1zd7h {
  width: 9px;
  height: 8px;
  x: 2.75px;
  y: 8px;
  rx: 4px;
}

</style>
