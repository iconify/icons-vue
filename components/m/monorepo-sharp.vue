<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f2zhoqb2c"/><path class="m7bvkw7gm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:monorepo-sharp" /></template>
<style>
.f2zhoqb2c {
  d: path("M2.75 7.25v-2.5h7.1l.6.8L11.55 7l.6.8h9.1v11.45H2.75v-2.5Z");
}

.m7bvkw7gm {
  d: path("M5 11.5h3v3H5zm5.5 0h3v3h-3zm5.5 0h3v3h-3z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
