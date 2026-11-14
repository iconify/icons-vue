<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuw01m0ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-fence" /></template>
<style>
.iuw01m0ls {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 19.5v-13L4 4.5l1.25 2v13m2.75 0v-13l1.25-2l1.25 2v13m3 0v-13l1.25-2l1.25 2v13m2.75 0v-13l1.25-2l1.25 2v13m-16-9.25H8m2.5 0h3m2.5 0h2.75M5.25 15.5H8m2.5 0h3m2.5 0h2.75");
}

</style>
