<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2i1rxmqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:zero-energy" /></template>
<style>
.w2i1rxmqp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.148 5.587l-3.981 5.226A1.362 1.362 0 0 0 7.25 13h.943a1.5 1.5 0 0 1 1.474 1.776L9.25 17a.853.853 0 0 0 1.543.637l3.658-5.365A1.453 1.453 0 0 0 13.25 10h-.798a1.5 1.5 0 0 1-1.449-1.886L11.5 6.25a.768.768 0 0 0-1.352-.663M14.75 18l2 2L21 15.75");
}

</style>
