<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rmorr4b8l"/><path class="tqebejbhh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mana-crystal-sharp" /></template>
<style>
.rmorr4b8l {
  d: path("m11.21 4.21l3.08 3.08L15 8v8.5l-.71.71l-3.08 3.08l-.71.71l-.71-.71l-3.08-3.08L6 16.5V8l.71-.71l3.08-3.08l.71-.71z");
}

.tqebejbhh {
  d: path("M6.25 8.25L10.5 11l4.25-2.75M10.5 11v9.25M18.25 3l.33 2.42l2.42.33l-2.42.33l-.33 2.42l-.33-2.42l-2.42-.33l2.42-.33z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
