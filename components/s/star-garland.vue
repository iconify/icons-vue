<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nyuk6gbac"/><path class="s6d2znber"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:star-garland" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nyuk6gbac {
  d: path("M2.5 7q9.5 6 19 0M6.367 9.744l.019.038a1.5 1.5 0 0 0 1.129.82l.041.006a.41.41 0 0 1 .227.699l-.029.029a1.5 1.5 0 0 0-.432 1.328l.007.04a.41.41 0 0 1-.594.432l-.037-.019a1.5 1.5 0 0 0-1.396 0l-.037.019a.41.41 0 0 1-.594-.432l.007-.04a1.5 1.5 0 0 0-.432-1.328l-.029-.029a.41.41 0 0 1 .227-.699l.041-.006a1.5 1.5 0 0 0 1.129-.82l.019-.038a.41.41 0 0 1 .734 0");
}

.s6d2znber {
  d: path("m12.367 10.994l.019.038a1.5 1.5 0 0 0 1.129.82l.041.006a.41.41 0 0 1 .227.699l-.029.029a1.5 1.5 0 0 0-.432 1.328l.007.04a.41.41 0 0 1-.594.432l-.037-.019a1.5 1.5 0 0 0-1.396 0l-.037.019a.41.41 0 0 1-.594-.432l.007-.04a1.5 1.5 0 0 0-.432-1.328l-.029-.029a.41.41 0 0 1 .227-.699l.041-.006a1.5 1.5 0 0 0 1.129-.82l.019-.038a.41.41 0 0 1 .734 0m6-1.25l.019.038a1.5 1.5 0 0 0 1.129.82l.041.006a.41.41 0 0 1 .227.699l-.029.029a1.5 1.5 0 0 0-.432 1.328l.007.04a.41.41 0 0 1-.594.432l-.037-.019a1.5 1.5 0 0 0-1.396 0l-.037.019a.41.41 0 0 1-.594-.432l.007-.04a1.5 1.5 0 0 0-.432-1.328l-.029-.029a.41.41 0 0 1 .227-.699l.041-.006a1.5 1.5 0 0 0 1.129-.82l.019-.038a.41.41 0 0 1 .734 0");
}

</style>
