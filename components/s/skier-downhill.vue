<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wdden06ut"/><path class="w5vmnrbke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skier-downhill" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w5vmnrbke {
  d: path("M13.25 9.25L17 11.5l2.5 5.75M3.5 16l17 4.75M2.5 8h4m-3 3h3");
}

.wdden06ut {
  d: path("M13 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM13.5 8L10 12l3.5 3.5l-2 2.75");
}

</style>
