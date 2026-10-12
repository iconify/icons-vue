<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_0q68bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:overalls-sharp" /></template>
<style>
.k_0q68bxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5.75h7V11h2.5l.12.99l1.01 8.27l.12.99H14l-.32-.95l-1.36-4.1l-.32-.95l-.32.95l-1.36 4.1l-.32.95H4.25l.12-.99l1.01-8.27l.12-.99H8V5.75zm-.25.75l-2-3.75m8.5 3.75l2-3.75m-7 5.75h3.5");
}

</style>
