<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o415c92oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:neuron" /></template>
<style>
.o415c92oq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm5.25 2.25C12 12 13.5 14 15.5 16l3 3M7.5 7.5h.01m-.01-3v-2m-3 5h-2m2.75 2.25l-2 2m6.5-6.5l2-2m-8.5 8.5l-.75 1.5m9.25-10l1.5-.75M18.5 19l3 .25m-3-.25l.75 2.75M18.5 19l2.5-2.25");
}

</style>
