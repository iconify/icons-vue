<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><circle class="o5grrub_r"/><path class="sgqlgqbnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:post-video-sharp" /></template>
<style>
.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.o5grrub_r {
  cx: 7px;
  cy: 7px;
  r: 1.5px;
}

.sgqlgqbnt {
  d: path("M10.5 7H17M2.75 10.5h18.5M10.5 13.4v4.2l-.029 1.394l1.179-.744l3.25-2.1l1.129-.65l-1.129-.65l-3.25-2.1l-1.179-.744z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
