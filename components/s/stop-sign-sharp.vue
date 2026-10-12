<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x4uaf6b-u"/><path class="f8nyyerwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stop-sign-sharp" /></template>
<style>
.f8nyyerwy {
  d: path("M8.75 12.75v-3m2.3 2.25V8.25m2.3 3.75V8.75m2.3 4V10.5m-6.9 2.25V17h6.9v-4.25m-6.9 1.5L7 12.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x4uaf6b-u {
  d: path("m20.25 16.17l-4.08 4.08l-.53.53H8.36l-.53-.53l-4.08-4.08l-.53-.53V8.36l.53-.53l4.08-4.08l.53-.53h7.28l.53.53l4.08 4.08l.53.53v7.28z");
}

</style>
