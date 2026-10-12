<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="z89u07baw"/><path class="j_ilo2wrs"/><path class="x_ptlgq7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pet-carrier-sharp" /></template>
<style>
.j_ilo2wrs {
  d: path("M2.75 19.5v-7c0-4 4.25-6.25 9.25-6.25s9.25 2.25 9.25 6.25v8.25H2.75z");
}

.x_ptlgq7r {
  d: path("M5.75 17.75V14a3.75 3.75 0 0 1 7.5 0v3.75Zm2.5-7.25v7.25m2.5-7.25v7.25m5.5-5.25h2m-2 3h2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z89u07baw {
  d: path("M10 6.4V4h4v2.4");
}

</style>
