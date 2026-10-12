<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f8bhvigpj"/><path class="ww9u57bwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tawa-sharp" /></template>
<style>
.f8bhvigpj {
  d: path("M4.5 16.25c2-2.5 13-2.5 15 0c-2 1.75-13 1.75-15 0Z");
}

.ww9u57bwy {
  d: path("m5 15.5l-2.25-.75V18L5 17.25m14-1.75l2.25-.75V18L19 17.25m-11.5-7a4.5 1.25 0 1 0 9 0a4.5 1.25 0 1 0-9 0ZM10 7.5c-.6-.6.6-1.2 0-2m4 2c-.6-.6.6-1.2 0-2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
