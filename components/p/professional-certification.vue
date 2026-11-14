<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ngeb2obqe"/><path class="m5nf17byo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:professional-certification" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m5nf17byo {
  d: path("m9.5 9.75l1.75 1.75L14.5 8");
}

.ngeb2obqe {
  d: path("m12.776 3.102l.196.152a1.75 1.75 0 0 0 1.31.351l.244-.034a1.27 1.27 0 0 1 1.345.777l.094.228a1.75 1.75 0 0 0 .959.959l.228.094a1.27 1.27 0 0 1 .777 1.345l-.034.244a1.75 1.75 0 0 0 .351 1.31l.152.196a1.27 1.27 0 0 1 0 1.552l-.152.196a1.75 1.75 0 0 0-.351 1.31l.034.244a1.27 1.27 0 0 1-.777 1.345l-.228.094a1.75 1.75 0 0 0-.959.959l-.094.228a1.27 1.27 0 0 1-1.345.777l-.244-.034a1.75 1.75 0 0 0-1.31.351l-.196.152a1.27 1.27 0 0 1-1.552 0l-.196-.152a1.75 1.75 0 0 0-1.31-.351l-.244.034a1.27 1.27 0 0 1-1.345-.777l-.094-.228a1.75 1.75 0 0 0-.959-.959l-.228-.094a1.27 1.27 0 0 1-.777-1.345l.034-.244a1.75 1.75 0 0 0-.351-1.31l-.152-.196a1.27 1.27 0 0 1 0-1.552l.152-.196a1.75 1.75 0 0 0 .351-1.31l-.034-.244a1.27 1.27 0 0 1 .777-1.345l.228-.094a1.75 1.75 0 0 0 .959-.959l.094-.228a1.27 1.27 0 0 1 1.345-.777l.244.034a1.75 1.75 0 0 0 1.31-.351l.196-.152a1.27 1.27 0 0 1 1.552 0M9 15.75L7.5 21l2.5-1l2 1.5m3-5.75L16.5 21L14 20l-2 1.5");
}

</style>
