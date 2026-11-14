<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ugiss7l0k"/><path class="ktpg_ebwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:star-sticker" /></template>
<style>
.ktpg_ebwv {
  d: path("M19 17c-2.5 0-5 2-5.5 4.5");
}

.ugiss7l0k {
  d: path("m12 3.25l2.645 5.609l6.152.783l-4.517 4.249l1.157 6.092L12 17l-5.437 2.983l1.157-6.092l-4.517-4.249l6.152-.783Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
