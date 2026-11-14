<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpstchsfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soda-maker" /></template>
<style>
.vpstchsfy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3h4v3c2 1 2.5 2 2.5 4v8h-9v-8c0-2 .5-3 2.5-4ZM4.5 18h15v3.5h-15Zm6.5-3h.01M13 11.5h.01");
}

</style>
