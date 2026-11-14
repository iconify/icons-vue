<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irf0p6gra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:menswear-department" /></template>
<style>
.irf0p6gra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.699 3h.602a1.5 1.5 0 0 1 1.488 1.686l-.125 1A1.5 1.5 0 0 1 12.176 7h-.352a1.5 1.5 0 0 1-1.488-1.314l-.125-1A1.5 1.5 0 0 1 11.699 3m.11 4h.382a1.5 1.5 0 0 1 1.486 1.297l1.222 8.966a1.5 1.5 0 0 1-.425 1.263l-1.413 1.413a1.5 1.5 0 0 1-2.122 0l-1.413-1.413a1.5 1.5 0 0 1-.425-1.263l1.222-8.966A1.5 1.5 0 0 1 11.809 7");
}

</style>
