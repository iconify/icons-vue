<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz2goj9py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:people-count" /></template>
<style>
.hz2goj9py {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM7.5 20c0-4 2-6.5 4.5-6.5c1.244 0 2.364.619 3.175 1.733M2.5 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm0 8.5c0-2.25.75-3.5 2-3.75m13-4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM18 15v6m-3-3h6");
}

</style>
