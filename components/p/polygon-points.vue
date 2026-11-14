<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c51ulj9bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:polygon-points" /></template>
<style>
.c51ulj9bv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.247 5.171l.988.156m-3.159 12.314l-1.717-.813m-2.49-5.936l.759-2.276M6.5 4.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM16 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm2.25 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-5.75 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM3 15a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
