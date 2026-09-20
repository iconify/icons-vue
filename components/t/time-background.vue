<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ts895odtg"/><path class="hb09rs_2k"/><path class="b577rkbnf"/><path class="utp8q6b2s"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:time-background" /></template>
<style>
.b577rkbnf {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 9.01a2.99 2.99 0 1 0 0 5.98a2.99 2.99 0 0 0 0-5.98M8.5 12a3.5 3.5 0 1 1 7 0a3.5 3.5 0 0 1-7 0");
}

.ft5dv1b6b {
  fill: none;
}

.hb09rs_2k {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 8.015C4 6.902 4.929 6 6.074 6h11.852C19.07 6 20 6.902 20 8.015v7.97C20 17.098 19.071 18 17.926 18H6.074C4.929 18 4 17.098 4 15.985zm2.074-1.528c-.868 0-1.573.685-1.573 1.527v7.971c0 .843.705 1.528 1.573 1.528h11.852c.868 0 1.573-.685 1.573-1.528v-7.97c0-.844-.706-1.528-1.573-1.528z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ts895odtg {
  fill: var(--svg-color--6784ff, #6784ff);
  d: path("M24 0H0v24h24z");
}

.utp8q6b2s {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.75 11c.148 0 .25.12.25.268V12.5h1.231c.149 0 .269.102.269.25s-.12.25-.269.25H11.5v-1.732c0-.148.102-.268.25-.268");
}

</style>
