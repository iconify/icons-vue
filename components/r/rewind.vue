<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjo8nzb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rewind" /></template>
<style>
.mjo8nzb6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.02 6.61l-6.54 4.53q-1.23.86 0 1.72l6.54 4.53q1.23.86 1.23-.64v-9.5q0-1.5-1.23-.64m-9.5 0l-6.54 4.53q-1.23.86 0 1.72l6.54 4.53q1.23.86 1.23-.64v-9.5q0-1.5-1.23-.64");
}

</style>
