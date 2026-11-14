<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9_jcvytg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:syringe-lab" /></template>
<style>
.q9_jcvytg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.929 14.828L12 7.757L16.243 12l-7.071 7.071Zm9.192-4.949l5.657-5.657M4.575 19.425L7.05 16.95m-4.242.707l3.535 3.535m3.182-10.96l4.243 4.243");
}

</style>
