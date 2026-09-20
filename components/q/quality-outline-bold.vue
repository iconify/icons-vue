<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yoftwf7ei"/><path class="rt_zplbzl"/><path class="ir3tk2beb"/><path class="m8rhztbam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quality-outline-bold" /></template>
<style>
.ir3tk2beb {
  d: path("M8 14v7");
}

.m8rhztbam {
  d: path("M16 14v7");
}

.rt_zplbzl {
  d: path("m9 9 2 2 4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yoftwf7ei {
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9");
}

</style>
