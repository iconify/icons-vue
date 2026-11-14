<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvafgd7jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:repo-wiki" /></template>
<style>
.gvafgd7jl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6Q9 3.75 3 4.5v14q6-.75 9 1.5q3-2.25 9-1.5v-14q-6-.75-9 1.5Zm0 0v14M5.75 9.5h3.5m5.5 0h3.5m-3.5 3.5h3.5");
}

</style>
