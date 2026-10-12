<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc0nbubbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:waterfall-sharp" /></template>
<style>
.fc0nbubbu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v4.5H2.75zM8 10v6m4-6v8m4-8v6M2.75 21.25c1.54 0 1.54-1.25 3.08-1.25s1.54 1.25 3.08 1.25S10.45 20 11.99 20s1.54 1.25 3.08 1.25S16.61 20 18.15 20s1.54 1.25 3.08 1.25");
}

</style>
