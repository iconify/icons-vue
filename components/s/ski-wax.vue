<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s9y3tt6_a"/><path class="tyqpq712i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ski-wax" /></template>
<style>
.s9y3tt6_a {
  d: path("M5 21V9.5L11 3h8v14.5L13 21Z");
}

.tyqpq712i {
  d: path("M5 9.5h8V21m0-11.5L19 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
