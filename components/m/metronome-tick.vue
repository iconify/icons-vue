<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a_3-obb5p"/><path class="e9fltbcec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:metronome-tick" /></template>
<style>
.a_3-obb5p {
  d: path("M13.295 20.5H6.741q-.099 0-.198-.011q-.099-.012-.196-.034q-.096-.022-.19-.056q-.094-.033-.183-.076q-.089-.044-.173-.097t-.161-.116t-.147-.134t-.131-.149q-.061-.079-.113-.163q-.052-.085-.093-.175q-.042-.09-.074-.184q-.031-.095-.052-.192T5 18.917t-.008-.198t.015-.198t.037-.195l3.625-14.5q.035-.141.093-.274t.137-.255t.178-.229t.212-.197q.115-.089.243-.159q.127-.069.265-.117q.137-.047.28-.071t.289-.024h1.268q.145 0 .289.024q.143.024.28.071q.138.048.265.117q.128.07.243.159q.114.09.212.197t.178.229q.079.122.137.255t.093.274l2.954 11.815M10.5 17l6-12.5");
}

.e9fltbcec {
  d: path("m14.75 18l2 2L21 15.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
