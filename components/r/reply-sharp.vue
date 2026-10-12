<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fmeosdblm"/><path class="kspidacpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reply-sharp" /></template>
<style>
.fmeosdblm {
  d: path("m9.25 5.25l-5.5 5.5l5.5 5.5");
}

.kspidacpp {
  d: path("M3.75 10.75h9.5a7 7 0 0 1 7 7v1");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
