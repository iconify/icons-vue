<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idqtrbc3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shovel" /></template>
<style>
.idqtrbc3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.88 9.18l6.94 6.94l-2.92 2.92a4.9 4.9 0 0 1-6.94-6.94Zm3.47 3.47l5.29-5.29m.18-3.83l3.65 3.65m-1.82-1.83l-2.01 2.01");
}

</style>
