<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjpzjjbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mashrabiya-sharp" /></template>
<style>
.sjpzjjbdl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 2.75H17.5l.47.58l1.31 1.59l.47.58H4.25l.47-.58l1.31-1.59l.47-.58zm-2 2.75h13.5V18H5.25v-1Zm6.75 0V18m-6.75-6.25h13.5M7.5 18h9.75l-.46.59l-1.58 2.07l-.46.59h-5.5l-.46-.59l-1.58-2.07l-.46-.59z");
}

</style>
