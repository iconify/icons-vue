<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dlg57oe5d"/><path class="jg7dhrbvi"/><path class="zf0ibxbza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mail-stack" /></template>
<style>
.dlg57oe5d {
  d: path("M6 7.5h9a3.5 3.5 0 0 1 3.5 3.5v5.5A3.5 3.5 0 0 1 15 20H6a3.5 3.5 0 0 1-3.5-3.5V11A3.5 3.5 0 0 1 6 7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jg7dhrbvi {
  d: path("M5.5 4.5h14a2 2 0 0 1 2 2v10");
}

.zf0ibxbza {
  d: path("m6 11l4.5 3l4.5-3");
}

</style>
