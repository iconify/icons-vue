<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v8lntgbin"/><path class="n7jkyzbmj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:telehealth-visit" /></template>
<style>
.n7jkyzbmj {
  d: path("M7 2.5V7c0 1.75 1.25 3 2.75 3s2.75-1.25 2.75-3V2.5M9.75 10v1.5c0 1.25 1 2 2.25 2s2-1 2-1.75m0-.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v8lntgbin {
  d: path("M3.5 5h17v11h-17ZM2 19h20");
}

</style>
