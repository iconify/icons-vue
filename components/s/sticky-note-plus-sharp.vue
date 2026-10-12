<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="d72hkkb0i"/><path class="eel4-ib9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sticky-note-plus-sharp" /></template>
<style>
.d72hkkb0i {
  d: path("M5.75 3.75h14.5V15l-1.41 1.41l-2.43 2.43L15 20.25H3.75V3.75z");
}

.eel4-ib9x {
  d: path("M20.25 15H15v5.25M7.5 8.75h9m-9 3.75H13");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
