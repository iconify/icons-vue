<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h29n_cogh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sandbag-carry" /></template>
<style>
.h29n_cogh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 7c-4.5 2-6.5 5.5-6.5 9S5 21.5 9 21.5h3c1.154 0 2.182-.166 3.062-.487m2.306-9.379C16.337 9.785 14.579 8.146 12 7M9 7L7 2.5h7L12 7M7.5 7h6M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
