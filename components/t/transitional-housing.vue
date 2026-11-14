<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hea6d0bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:transitional-housing" /></template>
<style>
.hea6d0bmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.244 20.5H3.5v-10L12 3.25l8.5 7.25v2.856M15 18h6.25m-2.75-2.75L21.25 18l-2.75 2.75");
}

</style>
