<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mm4qtlf9r"/><path class="pn61g8bmj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:right-angle-sharp" /></template>
<style>
.mm4qtlf9r {
  d: path("M4.75 3.75v15.5h15.5");
}

.pn61g8bmj {
  d: path("M7.75 16.25h3v-3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
