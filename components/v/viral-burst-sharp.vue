<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="a6ufm_sgj"/><path class="y4mqir5uc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:viral-burst-sharp" /></template>
<style>
.a6ufm_sgj {
  d: path("m12.65 3.26l.64.74l.65.76l.95-.33l.92-.33l.94-.33l.19.99l.18.95l.18.99l.99.18l.95.18l.99.19l-.33.94l-.33.92l-.33.95l.76.65l.74.64l.76.65l-.76.65l-.74.64l-.76.65l.33.95l.33.92l.33.94l-.99.19l-.95.18l-.99.18l-.18.99l-.18.95l-.19.99l-.94-.33l-.92-.33l-.95-.33l-.65.76l-.64.74l-.65.76l-.65-.76l-.64-.74l-.65-.76l-.95.33l-.92.33l-.94.33l-.19-.99l-.18-.95l-.18-.99l-.99-.18l-.95-.18l-.99-.19l.33-.94l.33-.92l.33-.95l-.76-.65l-.74-.64L2.5 12l.76-.65l.74-.64l.76-.65l-.33-.95l-.33-.92l-.33-.94l.99-.19l.95-.18l.99-.18l.18-.99l.18-.95l.19-.99l.94.33l.92.33l.95.33l.65-.76l.64-.74l.65-.76z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y4mqir5uc {
  d: path("m9.25 14.75l5.5-5.5m-4.5 0h4.5v4.5");
}

</style>
