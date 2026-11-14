<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lznltodja"/><path class="h8bx5zm3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:window-open-heating-off" /></template>
<style>
.h8bx5zm3t {
  d: path("m16.753 13.114l-.628.386q-.121.075-.258.115q-.136.04-.278.043t-.281-.031t-.262-.104t-.226-.169t-.173-.222q-.072-.123-.11-.26q-.037-.138-.037-.28V4.346q0-.036.002-.071q.002-.036.007-.071l.011-.07l.016-.07q.009-.034.021-.068l.024-.066l.029-.065l.033-.063l.037-.061l.041-.058q.022-.029.045-.056t.048-.052t.051-.049t.055-.046l.057-.043q.029-.02.06-.038t.062-.034q.032-.017.064-.031l.066-.026l.068-.022q.034-.01.069-.017t.07-.013t.071-.009t.071-.004t.071.001t.071.005l.07.01q.035.006.07.015t.068.018l.068.024q.033.012.065.027q.033.015.064.032l.836.45q.089.048.171.107q.082.06.155.13t.136.149t.115.166t.091.179t.067.191q.027.097.04.198q.014.1.014.201v6.516q0 .158-.033.312t-.097.298t-.156.271t-.21.233M8.5 2.5v12m-6-6h6m10 6.75c1.5 1.25 2.75 2.5 2.75 3.75a2.75 2.75 0 0 1-5.5 0c0-1.25 1.25-2.5 2.75-3.75m-2 1.25l5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lznltodja {
  d: path("M4.25 2.5h8.5a1.75 1.75 0 0 1 1.75 1.75v8.5a1.75 1.75 0 0 1-1.75 1.75h-8.5a1.75 1.75 0 0 1-1.75-1.75v-8.5A1.75 1.75 0 0 1 4.25 2.5");
}

</style>
