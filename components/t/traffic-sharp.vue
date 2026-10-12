<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="s_ez8tq1z"/><path class="rky71driu"/><path class="h2qnisb0h"/><path class="m--5damoa"/><path class="o8-81ebgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:traffic-sharp" /></template>
<style>
.h2qnisb0h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.14 15.08l.72-1.66l.39-.92h8.5l.39.92l.72 1.66l.39.92v3.25H2.75V16z");
}

.m--5damoa {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 16.25h.01m5.49 0h.01");
}

.o8-81ebgi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 19.25v2m7.5-2v2");
}

.rky71driu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.75 6.5h.01m5.49 0h.01");
}

.s_ez8tq1z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.14 5.33l.72-1.66l.39-.92h8.5l.39.92l.72 1.66l.39.92v3H9.75v-3z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
