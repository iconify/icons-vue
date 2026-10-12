<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pw7p-85ys"/><path class="v-p-0wj2u"/><path class="mdv2kmbso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:picture-frame-sharp" /></template>
<style>
.mdv2kmbso {
  d: path("m6.25 16.25l3.75-4l3 3l1.75-1.75l3 2.75");
}

.pw7p-85ys {
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

.v-p-0wj2u {
  d: path("M6.25 7.25h11.5v9.5H6.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
