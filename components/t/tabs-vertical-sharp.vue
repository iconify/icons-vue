<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pw7p-85ys"/><path class="q1pdbxbbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tabs-vertical-sharp" /></template>
<style>
.pw7p-85ys {
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

.q1pdbxbbp {
  d: path("M9.25 3.75v5h12m-6-5v5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
