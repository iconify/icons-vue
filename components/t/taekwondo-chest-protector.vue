<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko-4q6tim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:taekwondo-chest-protector" /></template>
<style>
.ko-4q6tim {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 3l4.5 8.5L16.5 3H19c0 4 .5 6 1 7v9a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-9c.5-1 1-3 1-7ZM4 15.5h16");
}

</style>
